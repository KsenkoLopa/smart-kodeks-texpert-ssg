## ПОЛНЫЙ СПИСОК АЛЕРТОВ

Здесь представлена информация обо всех алертах, существующих и использующихся по состоянию на 15.08.2024г.

По мере развития СМАРТа могут появляться новые, данный раздел будет, соответственно, актуализироваться.

Обращаем внимание, что некоторые алерты в своем наименовании содержат слово Count. 

Как это понимать? Данный алерт приходит в том случае когда на подконтрольном СМАРТу объекте или объектах возникла массовая однотипная ошибка.
Поскольку алерты приходят в Telegram-канал, у этой платформы технически есть ограничение на количество и частоту входящих сообщений.
Если эти значения оказываются превышены - Telegram выдаст сообщение об ошибке "Error sending messages, check logs".
В этом случае следует незамедлительно сообщить об этом разработчику СМАРТа.
Для того чтобы обойти такую техническую особенность Telegram - и был создан такой тип алертов.

---
### Алерты на ошибки с базами данных и operup

| **Имя алерта**              | **Краткое описание алерта**                                                                                               | **Адрес с полным описанием и способами устранения**                 |
|-----------------------------|---------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| KodeksDBerrorsNoCode        | Есть ошибки, связанные с БД ПК, но код ошибки СМАРТ не смог определить.                                                   | http://smart.uniclass.ru/docs/errors/KodeksDBerrorsNoCode.md        |
| KodeksDBerrorsNoCodeCount   | Есть ошибки, связанные с БД ПК, но код ошибки СМАРТ не смог определить. **Много однотипных ошибок по многим БД ПК.**      | http://smart.uniclass.ru/docs/errors/KodeksDBerrorsNOCodeCount.md   |
| KodeksDBerrorsCode2007      | Ошибка БД 2007 - Нет прав на использование данной БД.                                                                     | http://smart.uniclass.ru/docs/errors/KodeksDBerrorsCode2007.md      |
| KodeksDBerrorsCode2007Count | Ошибка БД 2007 - Нет прав на использование данной БД. **Много однотипных ошибок по многим БД ПК.**                        | http://smart.uniclass.ru/docs/errors/KodeksDBerrorsCode2007Count.md |
| KodeksDBerrorsCodeXXX       | Выявлены разнообразные ошибки с БД ПК.                                                                                    | http://smart.uniclass.ru/docs/errors/KodeksDBerrorsCodeXXX.md       |
| KodeksDBerrorsCodeXXXCount  | Выявлены разнообразные ошибки с БД ПК. **Много однотипных ошибок по многим БД ПК.**                                       | http://smart.uniclass.ru/docs/errors/KodeksDBerrorsCodeXXXCount.md  |
| KodeksDBOperUpToOld         | Дата операпов старше 3 дней                                                                                               | http://smart.uniclass.ru/docs/errors/KodeksDBOperUpToOld.md         |
| KodeksDBOperUpToOldCount    | Дата операпов старше 3 дней. **Много однотипных ошибок по многим операпам.**                                              | http://smart.uniclass.ru/docs/errors/KodeksDBOperUpToOldCount.md    |

---
### Алерты, связанные с сетевой доступностью

| **Имя алерта**           | **Краткое описание алерта**                                                                                                 | **Адрес с полным описанием и способами устранения**              |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------|
| KodeksBehindProxyDown    | На сервере с ПК ТЭ есть проблемы с reverse-proxy.                                                                           | http://smart.uniclass.ru/docs/errors/KodeksBehindProxyDown.md    |
| KodeksHttp200Status      | На запросы ПК ТЭ не отвечает HTTP 200.                                                                                      | http://smart.uniclass.ru/docs/errors/KodeksHttp200Status.md      |
| KodeksHttp200StatusCount | На запросы ПК ТЭ не отвечает HTTP 200. **Много однотипных ошибок по многим хостам**                                         | http://smart.uniclass.ru/docs/errors/KodeksHttp200StatusCount.md | 
| KodeksIcmp               | Проверка на доступность ПК ТЭ командой ping по протоколу ICMP не проходит.                                                  | http://smart.uniclass.ru/docs/errors/KodeksIcmp.md               |
| KodeksIcmpCount          | Проверка на доступность ПК ТЭ командой ping по протоколу ICMP не проходит. <br/>**Много однотипных ошибок на доступность.** | http://smart.uniclass.ru/docs/errors/KodeksIcmpCount.md          |
| KodeksTcpStatus          | Проверяется, что порт-монитор ПК ТЭ готов "слушать".                                                                        | http://smart.uniclass.ru/docs/errors/KodeksTcpStatus.md          |
| KodeksTcpStatusCount     | Проверяется, что порт-монитор ПК ТЭ готов "слушать". **Много однотипных ошибок по многим хостам**                           | http://smart.uniclass.ru/docs/errors/KodeksTcpStatusCount.md     |

---
### Алерты, связанные с простыми онлайн-доступами

| **Имя алерта**              | **Краткое описание алерта**                                                                                                    | **Адрес с полным описанием и способами устранения**                 |
|-----------------------------|--------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| OnlineBillingDocsLeft150    | Биллинг на открытие документов - меньше 150шт.                                                                                 | http://smart.uniclass.ru/docs/errors/OnlineBillingDocsLeft150.md    |
| OnlineBillingDocsLeft50     | Биллинг на открытие документов - меньше 50шт.                                                                                  | http://smart.uniclass.ru/docs/errors/OnlineBillingDocsLeft50.md     |
| OnlineBillingDocsLeftZero   | Биллинг на открытие документов - ноль.                                                                                         | http://smart.uniclass.ru/docs/errors/OnlineBillingDocsLeftZero.md   |
| OnlineBillingPrintLeft150   | Биллинг на печать документов - меньше 150шт.                                                                                   | http://smart.uniclass.ru/docs/errors/OnlineBillingPrintLeft150.md   |
| OnlineBillingPrintLeft50    | Биллинг на печать документов - меньше 50шт.                                                                                    | http://smart.uniclass.ru/docs/errors/OnlineBillingPrintLeft50.md    |
| OnlineBillingPrintLeftZero  | Биллинг на печать документов - ноль                                                                                            | http://smart.uniclass.ru/docs/errors/OnlineBillingPrintLeftZero.md  |
| OnlineBillingSearchLeft150  | Биллинг на поиск документов - меньше 150шт.                                                                                    | http://smart.uniclass.ru/docs/errors/OnlineBillingSearch150.md      |
| OnlineBillingSearchLeft50   | Биллинг на поиск документов - меньше 50шт.                                                                                     | http://smart.uniclass.ru/docs/errors/OnlineBillingSearch50.md       |
| OnlineBillingSearchLeftZero | Биллинг на поиск документов - ноль.                                                                                            | http://smart.uniclass.ru/docs/errors/OnlineBillingSearchLeftZero.md |
| OnlineBillingUploadLeft150  | Биллинг на выгрузку документов - меньше 150шт.                                                                                 | http://smart.uniclass.ru/docs/errors/OnlineBillingUploadLeft150.md  |
| OnlineBillingUploadLeft50   | Биллинг на выгрузку документов - меньше 50шт.                                                                                  | http://smart.uniclass.ru/docs/errors/OnlineBillingUploadLeft50.md   |
| OnlineBillingUploadLeftZero | Биллинг на выгрузку документов - ноль.                                                                                         | http://smart.uniclass.ru/docs/errors/OnlineBillingUploadLeftZero.md |
| OnlineLoginFailed           | Авторизация по онлайн-доступу не прошла.                                                                                       | http://smart.uniclass.ru/docs/errors/OnlineLoginFailed.md           |
| OnlineUserActivityIsLow10   | Проверяется уровень показателя активности (% исп.док.) на 10ое число месяца - <br/>алерт когда показатель ниже 3%.             | http://smart.uniclass.ru/docs/errors/OnlineUserActivityIsLow10.md   |
| OnlineUserActivityIsLow20   | Проверяется уровень показателя активности (% исп.док.) на 20ое число месяца - <br/>алерт когда показатель ниже 10%.            | http://smart.uniclass.ru/docs/errors/OnlineUserActivityIsLow20.md   |
| OnlineUserActivityIsLow30   | Проверяется уровень показателя активности (% исп.док.) на 30ое число месяца - <br/>алерт когда показатель ниже 15%.            | http://smart.uniclass.ru/docs/errors/OnlineUserActivityIsLow30.md   |
| KodeksSearchIsEmpty         | Проверяется, что по поисковому запросу пользователя ПК ТЭ что-то нашел. <br/> Валидно и для установок, и для простых онлайнов. | http://smart.uniclass.ru/docs/errors/KodeksSearchIsEmpty.md         |


---
### Алерты, связанные с сетевой доступностью ПК ТЭ

| **Имя алерта**               | **Краткое описание алерта**                                                                          | **Адрес с полным описанием и способами устранения**                  |
|------------------------------|------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------|
| KodeksMaintenance            | ПК ТЭ в режиме тех.обслуживания.                                                                     | http://smart.uniclass.ru/docs/errors/KodeksMaintenance.md            |
| KodeksMaintenanceCount       | Большое количество (более 30 установок) ПК ТЭ оказались в режиме тех.обслуживания.                   | http://smart.uniclass.ru/docs/errors/KodeksMaintenanceCount.md       |
| KodeksNeedSupport            | На Главной странице ПК ТЭ появляется сервисное сообщение<br>о необходимости сервисного обслуживания. | http://smart.uniclass.ru/docs/errors/KodeksNeedSupport.md            |
| KodeksMaintenanceToLong      | ПК в режиме тех.обслуживания более 3 часов подряд.                                                   | http://smart.uniclass.ru/docs/errors/KodeksMaintenanceToLong.md      |
| KodeksMaintenanceToLongCount | ПК в режиме тех.обслуживания более 3 часов подряд. **Много однотипных ошибок по многим ПК ТЭ.**      | http://smart.uniclass.ru/docs/errors/KodeksMaintenanceToLongCount.md |

---
### Алерты, связанные с работой Менеджера лицензий

| **Имя алерта**  | **Краткое описание алерта**                                                  | **Адрес с полным описанием и способами устранения**     |
|-----------------|------------------------------------------------------------------------------|---------------------------------------------------------|
| LicmanIcmp      | Проверка на доступность Менеджера лицензий командой Ping по протоколу ICMP.  | http://smart.uniclass.ru/docs/errors/LicmanIcmp.md      |
| LicmanTcpStatus | Проверка, что порт-монитор Менеджера лицензий открыт и "слушает".            | http://smart.uniclass.ru/docs/errors/LicmanTcpStatus.md |

---
### Алерты, связанные с работой ключей защиты SenseLock

| **Имя алерта**             | **Краткое описание алерта**                                                   | **Адрес с полным описанием и способами устранения**                |
|----------------------------|-------------------------------------------------------------------------------|--------------------------------------------------------------------|
| KodeksOfflineSensLockCheck | Проверяется, что ключ SenseLock доступен.                                     | http://smart.uniclass.ru/docs/errors/KodeksOfflineSensLockCheck.md |
| KodeksOnlineSensLockCheck  | Проверяется, что ПК сообщает, что ключ SenseLock активен.                     | http://smart.uniclass.ru/docs/errors/KodeksOnlineSensLockCheck.md  |
| KodeksXmlSensLockStatus    | Проверяется, что информация о статусе ключа SenseLock присутствует в Sysinfo. | http://smart.uniclass.ru/docs/errors/KodeksXmlSensLockStatus.md    |

---
### Алерты, связанные с лицензией (рег.файлом и его работой, рабочими местами по лицензии)

| **Имя алерта**             | **Краткое описание алерта**                                                                                                                                                     | **Адрес с полным описанием и способами устранения**                |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|
| KodeksDetectOverUserError  | Проверяется ситуация, когда пользователь захотел зайти в ПК ТЭ, а ПК вернул ему, что <br/>**нет свободных рабочих мест для входа.**                                             | http://smart.uniclass.ru/docs/errors/KodeksDetectOverUserError.md  |
| KodeksLicenseExpiring2day  | Лицензия истечет через 2 дня.                                                                                                                                                   | http://smart.uniclass.ru/docs/errors/KodeksLicenseExpiring2day.md  |
| KodeksLicenseExpiring7day  | Лицензия истечет через 7 дней.                                                                                                                                                  | http://smart.uniclass.ru/docs/errors/KodeksLicenseExpiring7day.md  |
| KodeksLicenseExpiring90day | Лицензия истечет через 90 дней.                                                                                                                                                 | http://smart.uniclass.ru/docs/errors/KodeksLicenseExpiring90day.md |
| KodeksLimitsUsers          | Проверяется, что не осталось свободных рабочих мест по лицензии.                                                                                                                | http://smart.uniclass.ru/docs/errors/KodeksLimitsUsers.md          |
| KodeksUnsupportedButUsed   | Проверяется, что на установку, по которой прекращено обслуживание <br/>(но она при этом функциональна), происходит вход пользователей и есть данные об их деятельности в ПК ТЭ. | http://smart.uniclass.ru/docs/errors/KodeksUnsupportedButUsed.md   |

---
### Алерты, связанные с пользователями и их работой в ПК ТЭ

| **Имя алерта**              | **Краткое описание алерта**                                                                                                    | **Адрес с полным описанием и способами устранения**                 |
|-----------------------------|--------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| KodeksNewUser               | Проверяется, что в ПК ТЭ зарегистрировался новый пользователь.                                                                 | http://smart.uniclass.ru/docs/errors/KodeksNewUser.md               |
| KodeksUserActivityIsLow     | Проверяется, что Активность пользователей по установке не ниже 20.                                                             | http://smart.uniclass.ru/docs/errors/KodeksUserActivityIsLow.md     |
| KodeksUserAInvolvementIsLow | Проверяется, что Вовлеченность пользователей по установке не ниже 60%.                                                         | http://smart.uniclass.ru/docs/errors/KodeksUserAInvolvementIsLow.md |
| KodeksSearchIsEmpty         | Проверяется, что по поисковому запросу пользователя ПК ТЭ что-то нашел. <br/> Валидно и для установок, и для простых онлайнов. | http://smart.uniclass.ru/docs/errors/KodeksSearchIsEmpty.md         |
| KodeksSearchError           | Проверяется, что поисковый запрос корректно разбирается и <br/>обрабатывается поисковой машиной ПК ТЭ                          | http://smart.uniclass.ru/docs/errors/KodeksSearchError.md           |

---
### Прочие алерты

| **Имя алерта**        | **Краткое описание алерта**                                                                      | **Адрес с полным описанием и способами устранения**           |
|-----------------------|--------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| KodeksAuthNotWork     | Проверяется, что пользователи могут успешно проходить авторизацию в ПК ТЭ.                       | http://smart.uniclass.ru/docs/errors/KodeksAuthNotWork.md     |
| KodeksSppStatus       | Проверяется, что СПП работает.                                                                   | http://smart.uniclass.ru/docs/errors/KodeksSppStatus.md       |
| KodeksWarning         | Проверяется, что на установке нет каких-либо аварийных состояний                                 | http://smart.uniclass.ru/docs/errors/KodeksWarning.md         |
| SmartXMLfileIsToOld   | Проверяется, что СМАРТ регулярно получает выгрузки sysinfo                                       | http://smart.uniclass.ru/docs/errors/SmartXMLfileIsToOld.md   |
| KodeksDBLicensesZero  | Проверяется, что выгрузка sysinfo имеет заполненный блок с сроком действия лицензии по каждой БД | http://smart.uniclass.ru/docs/errors/KodeksDBLicensesZero.md  |


[Вернуться в Начало](000-intro.md)

[Вернуться к Оглавлению](index.md)
