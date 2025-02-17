# Внедрение smartupload на установке, размещенной в сервисе "Техэксперт.Облако"

Процесс такого внедрения не потребует никаких особых навыков, умений, времени на корректировки шаблонов каких-то файлов 
и всего такого прочего.

Процесс уже максимально упрощен.

Вот что нужно сделать:
- зайти в административную часть Техэксперта;
- создать там нового пользователя со следующими параметрами:

![Пользователь СМАРТ](img/implementation/smartonline-user.png "Пользователь СМАРТ")

Логин и пароль выдает разработчик СМАРТа.
Пользователь должен быть включен только в группу "Администратор".
При этом следует проверить (и установить, если необходимо) авторизацию на каталог /sysinfo - ее либо не должно быть 
(по умолчанию это так), либо авторизация только для группы "Администратор".

В противном случае СМАРТ-мониторинг не сможет запросить sysinfo с такой установки.

- передать разработчику веб-адрес установки;
- через некоторое время наблюдать за дашбордами, которые постепенно будут наполняться данными из подконтрольных установок.

Вот и все.

[Вернуться к началу](050-intro-smartuload-smartstatus.md)

[Вернуться к Оглавлению, если стало страшно](index.md)
