# SP-EFT-ProfileEditor
Программа для редактирования профиля игрока на сервере SPTarkov

### [Новая версия 2.0 для сервера SPT-AKI 2.2.0 доступна здесь](https://github.com/SkiTles55/SPT-AKI-Profile-Editor/releases/tag/2.0)
### [New version 2.0 for server SPT-AKI 2.2.0 available here](https://github.com/SkiTles55/SPT-AKI-Profile-Editor/releases/tag/2.0)

### Возможности:
* Уровень, никнейм, голос персонажа
* Установка обычных \ больших карманов
* Уровни застройки убежища
* Уровни отношений торговцев
* Статусы квестов
* Уровни скиллов \ владения оружия
* Изученные предметы
* Удаление \ добавление предметов в схроне (WIP), выдача денег
* Импорт \ экспорт \ удаление сборок оружия

### Особенности:
* Простой, интуитивно понятный интерфейс
* Мультиязычность, с возможностью редактирования локализации
* Автоматические бэкапы при каждом сохранении профиля

### Требования:
* .NET 5.0 (Версия 1.8 и выше)
* .NET Framework 4.6.1 (Версии 1.0 - 1.7)

## Начиная с версии 1.6 в конфигурационный файл PEOptions добавлены относительные пути к файлам сервера. Изменяя их, можно попробовать редактировать профиль на неподдерживаемом сервере (успех не гарантируется!!!).

Относительные пути для сервера SPT-AKI Alpha R7
```json
"FilesList": {
    "file_globals": "Aki_Data\\Server\\eft-database\\db\\globals.json",
    "file_items": "Aki_Data\\Server\\eft-database\\db\\templates\\items.json",
    "file_quests": "Aki_Data\\Server\\eft-database\\db\\templates\\quests.json",
    "file_usec": "Aki_Data\\Server\\eft-database\\db\\bots\\types\\usec.json",
    "file_bear": "Aki_Data\\Server\\eft-database\\db\\bots\\types\\bear.json",
    "file_areas": "Aki_Data\\Server\\eft-database\\db\\hideout\\areas.json",
    "file_serverexe": "Server.exe"
  }
```

[Версия 1.9 для серверов SPT-AKI 2.0.0](https://github.com/SkiTles55/SP-EFT-ProfileEditor/releases/tag/1.9)

[Версия 1.8 для серверов SPT-AKI 1.0.0 B*, 1.0.0 - 1.5.1](https://github.com/SkiTles55/SP-EFT-ProfileEditor/releases/tag/1.8)

[Версия 1.6 для серверов SPT-AKI Alpha R7](https://github.com/SkiTles55/SP-EFT-ProfileEditor/releases/tag/1.6)

[Версия 1.5 для серверов SPT-AKI Alpha R7](https://github.com/SkiTles55/SP-EFT-ProfileEditor/releases/tag/1.5)

[Версия 1.4 для серверов SPT-AKI Alpha R4/R5/R6](https://github.com/SkiTles55/SP-EFT-ProfileEditor/releases/tag/1.4)

[Версия 1.2 для серверов SPT-AKI Alpha R2](https://github.com/SkiTles55/SP-EFT-ProfileEditor/releases/tag/1.2)

[Версия 1.1 для серверов SPT-AKI Alpha](https://github.com/SkiTles55/SP-EFT-ProfileEditor/releases/tag/1.1)

[Версия 1.0 для серверов 0.12.7-R6](https://github.com/SkiTles55/SP-EFT-ProfileEditor/releases/tag/1.0)

![Скриншот1](https://github.com/SkiTles55/SP-EFT-ProfileEditor/blob/master/screenshots/1.JPG?raw=true)
![Скриншот2](https://github.com/SkiTles55/SP-EFT-ProfileEditor/blob/master/screenshots/2.JPG?raw=true)
![Скриншот3](https://github.com/SkiTles55/SP-EFT-ProfileEditor/blob/master/screenshots/3.JPG?raw=true)
![Скриншот4](https://github.com/SkiTles55/SP-EFT-ProfileEditor/blob/master/screenshots/4.JPG?raw=true)
![Скриншот5](https://github.com/SkiTles55/SP-EFT-ProfileEditor/blob/master/screenshots/5.JPG?raw=true)

# SP-EFT-ProfileEditor ENG Readme
Program for editing player profile on the SPTarkov Server

### Capabilities:
* Level, nickname, character voice  
* Switching between regular \ large pockets  
* Hideout building levels  
* Trader relationship levels  
* Quest statuses  
* Skill \ Mastering levels  
* Examined items  
* Removing \ adding items in stash (WIP), adding money 
* Import \ export \ removing weapon builds

### Features:  
* Simple, intuitive interface  
* Multilingual, with the ability to edit localization  
* Automatic backups every time you save your profile

### Requirements:
* .NET 5.0 (Version 1.8 and higher)
* .NET Framework 4.6.1 (Versions 1.0 - 1.7) 

## Starting from version 1.6, relative paths to server files have been added to the PEOptions configuration file. By changing them, you can try to edit the profile on an unsupported server (success is not guaranteed !!!).

Relative paths for server SPT-AKI Alpha R7
```json
"FilesList": {
    "file_globals": "Aki_Data\\Server\\eft-database\\db\\globals.json",
    "file_items": "Aki_Data\\Server\\eft-database\\db\\templates\\items.json",
    "file_quests": "Aki_Data\\Server\\eft-database\\db\\templates\\quests.json",
    "file_usec": "Aki_Data\\Server\\eft-database\\db\\bots\\types\\usec.json",
    "file_bear": "Aki_Data\\Server\\eft-database\\db\\bots\\types\\bear.json",
    "file_areas": "Aki_Data\\Server\\eft-database\\db\\hideout\\areas.json",
    "file_serverexe": "Server.exe"
  }
```

[Version 1.9 for SPT-AKI 2.0.0](https://github.com/SkiTles55/SP-EFT-ProfileEditor/releases/tag/1.9)

[Version 1.8 for SPT-AKI 1.0.0 B*, 1.0.0 - 1.5.1](https://github.com/SkiTles55/SP-EFT-ProfileEditor/releases/tag/1.8)

[Version 1.6 for SPT-AKI Alpha R7](https://github.com/SkiTles55/SP-EFT-ProfileEditor/releases/tag/1.6)

[Version 1.5 for SPT-AKI Alpha R7](https://github.com/SkiTles55/SP-EFT-ProfileEditor/releases/tag/1.5)

[Version 1.4 for SPT-AKI Alpha R4/R5/R6](https://github.com/SkiTles55/SP-EFT-ProfileEditor/releases/tag/1.4)

[Version 1.2 for SPT-AKI Alpha R2](https://github.com/SkiTles55/SP-EFT-ProfileEditor/releases/tag/1.2)

[Version 1.1 for SPT-AKI Alpha](https://github.com/SkiTles55/SP-EFT-ProfileEditor/releases/tag/1.1)

[Version 1.0 for 0.12.7-R6](https://github.com/SkiTles55/SP-EFT-ProfileEditor/releases/tag/1.0)
