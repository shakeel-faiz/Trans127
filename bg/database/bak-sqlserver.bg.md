{
  "date": "2023-06-12",
  "keywords": [
    "bak",
    "bak file",
    "Microsoft SQL Server Database Backup",
    "what is a bak file",
    "how to open bak file",
    "file",
    "bak file extension",
    "extension"
  ],
  "author": {
    "display_name": "Shakeel Faiz"
  },
  "draft": "false",
  "toc": true,
  "title": "BAK File Format - Microsoft SQL Server Database Backup",
  "description": "Научете за формата за архивиране на BAK SQL Server и API, които могат да създават и отварят BAK файлове.",
  "linktitle": "BAK SQL Server",
  "menu": {
    "docs": {
      "identifier": "database-bak-sqlserver",
      "parent": "database"
    }
  },
  "lastmod": "2023-06-12"
}

## Какво е BAK файл?

Файлът ".bak" в контекста на Microsoft SQL Server е резервен файлов формат, използван за съхраняване на копия на база данни на SQL Server. Тези файлове съдържат моментна снимка на базата данни в определен момент от време, включително нейната схема, данни и друга свързана информация. Те се генерират с помощта на вградената функция за архивиране и възстановяване на SQL Server и служат за няколко важни цели:

1. **Възстановяване на данни:** .bak файловете предоставят средство за възстановяване на база данни в случай на загуба на данни, повреда или други проблеми. Като възстановите база данни от .bak файл, можете да я върнете към предишно състояние, минимизирайки времето за престой и загубата на данни.

2. **Миграция и клониране:** Архивните файлове често се използват за мигриране на бази данни между сървъри или създаване на копия на бази данни за целите на тестване, разработка или отчитане. Те предлагат последователен и ефективен начин за преместване на бази данни между среди.

3. **Възстановяване в даден момент:** SQL Server ви позволява да извършвате възстановяване в даден момент с помощта на .bak файлове. Това означава, че можете да възстановите база данни до определен момент от време, което може да бъде от решаващо значение за съответствие с нормативните изисквания или одит на данни.

4. **Възстановяване след бедствие:** .bak файловете са критична част от планирането за възстановяване след бедствие. Те гарантират, че вашите данни са в безопасност и могат да бъдат възстановени бързо в случай на хардуерни повреди, природни бедствия или други катастрофални събития.

## Създайте .BAK файл в SQL Server

За да създадете .bak файл в SQL Server, обикновено използвате команди на SQL Server Management Studio (SSMS) или Transact-SQL (T-SQL) като BACKUP DATABASE или BACKUP LOG. Ето опростен пример за това как можете да създадете резервно копие на база данни с помощта на T-SQL:

```
BACKUP DATABASE YourDatabaseName
TO DISK = 'C:\Path\To\Your\BackupFile.bak'
```

## Възстановете .BAK файл в SQL Server

За да възстановите база данни от .bak файл, можете да използвате командата RESTORE DATABASE:

```
RESTORE DATABASE YourRestoredDatabaseName
FROM DISK = 'C:\Path\To\Your\BackupFile.bak'
```

## Как да отворя BAK файл в SQL Server?

За да отворите и получите достъп до данните, съхранени във файл ".bak", обикновено трябва да го възстановите в екземпляр на Microsoft SQL Server. Ето общите стъпки за отваряне на файл ".bak" с помощта на SQL Server Management Studio (SSMS):

1. **Стартирайте SQL Server Management Studio**: Отворете SSMS на вашия компютър. Обикновено можете да го намерите в менюто "Старт" или като потърсите "SQL Server Management Studio".

2. **Свържете се с екземпляр на SQL Server**: В SSMS се свържете с екземпляр на SQL Server, където искате да възстановите базата данни. Ще ви трябват необходимите разрешения, за да извършите тази операция.

3. **Възстановяване на база данни**:

    а. В панела Object Explorer от лявата страна разгънете екземпляра на SQL Server.

    b. Разгънете възела „Бази данни“.

    ° С. Щракнете с десния бутон върху „Бази данни“ и изберете „Възстановяване на база данни“.

4. **Посочете източник и дестинация**:

    а. В страницата „Общи“ на диалоговия прозорец „Възстановяване на база данни“ въведете име за новата база данни в полето „Към база данни“. Това ще бъде името на възстановената база данни.

    b. В секцията „Източник“ изберете „Устройство“ като тип носител за архивиране.

    ° С. Щракнете върху бутона "..." до полето "Устройство", за да прегледате файла ".bak", който искате да възстановите.

    д. Изберете файла „.bak“, който искате да отворите, и щракнете върху „OK“.

5. **Опции за възстановяване**: Прегледайте и конфигурирайте опциите за възстановяване според нуждите. Можете да посочите дали да презапишете съществуваща база данни, да зададете опции за възстановяване и др. Уверете се, че сте задали тези опции според вашите изисквания.

6. **Започнете възстановяването**: След като конфигурирате опциите за възстановяване, щракнете върху бутона „OK“ в диалоговия прозорец „Възстановяване на база данни“. SQL Server ще започне процеса на възстановяване.

7. **Достъп до възстановената база данни**: След успешно възстановяване можете да получите достъп до възстановената база данни в SQL Server Management Studio точно както всяка друга база данни. Можете да изпълнявате заявки, да преглеждате таблици и да работите с данните в базата данни.

## Други BAK файлове

Ето други типове файлове, които използват файловото разширение **.bak**.

**Database**
- [BAK - Database Backup File](/database/bak/)
- [BAK - Swiftpage Act! Database Backup](/database/bak-act/)

**Game**
- [BAK - Terraria World or Player Backup](/game/bak-terraria/)

**Misc**
- [BAK - Backup File](/misc/bak-backup/)
- [BAK - Chromium Bookmarks Backup](/misc/bak-chromium/)
- [BAK - Finale 2012 Score Backup](/misc/bak-finale/)
- [BAK - MobileTrans Backup](/misc/bak-mobiletrans/)
- [BAK - VEGAS Video Project Backup](/misc/bak-vegas/)

**Settings**
- [BAK - Holo Launcher Backup](/settings/bak-holo/)

## Препратки
* [Backup and restore a SQL Server database with SSMS](https://learn.microsoft.com/en-us/sql/relational-databases/backup-restore/quickstart-backup-restore-database?view=sql-server-ver16&tabs=ssms)