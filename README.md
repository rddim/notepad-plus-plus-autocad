 * [Синтаксис за оцветяване на команди](#Синтаксис-за-оцветяване-на-команди)
 * [Автоматично завършване на команди](#Автоматично-завършване-на-команди)
 * [Екранни снимки](#screenshots)
 * [Сваляне](../../releases/latest) на последната версия
 
--
 * [Highlight Syntax for AutoCAD](#highlight-syntax-for-autocad)
 * [Auto-Completion Functions](#auto-completion-functions)
 * [Screenshots](#screenshots)
 * [Download](../../releases/latest) latest release
 
---
#### Notepad++
--
Можете да изтеглите Notepad++ от [тук](http://notepad-plus-plus.org/)

Актуален български превод на Notepad++ можете да изтеглите от [тук](https://gist.github.com/rddim/bd37264898c3a17363e7437bcf1b4803)

---
#### Синтаксис за оцветяване на команди
--
Файловете от папка `userDefineLang` се внасят в Notepad++ чрез `Синтаксис` > `Дефиниране на синтаксис` > `Внасяне...`

  * **ACAD-Linetype.xml** - синтаксис за оцветяване на определени команди във файловете с типове `линии` (_*.lin_) за AutoCAD
  * **ACAD-Script.xml** - синтаксис за оцветяване на определени команди в `скрипт` файловете (_*.scr_) за AutoCAD
  * **ACAD-Shape-Hatch.xml** - синтаксис за оцветяване на определени команди в `shape` файловете (_*.shp_) и типовете `щриховки` (_*.pat_) за AutoCAD

> :warning: _Забележка:_
>
> При обновяване на наличните такива, те трябва предварително да се премахнат, тъй като се получава дублиране.

--
#### Автоматично завършване на команди
--
Файловете от папка `plugins` > `APIs` се поставят в папка `Notepad++` > `plugins` > `APIs`<sup><sup><b>[1]</b></sup></sup>

За да работи, автоматичното завършване трябва да бъде разрешено в `Настройки` > `Предпочитания...` > `Авто-завършване` > `Завършване на функции и думи`

> :warning: _Забележка:_
>
> Синтаксисът за оцветяване на команди трябва да бъде наличен в Notepad++

  * **acad-linetype.xml** - автоматично завършване на наличните команди<sup><sup><b>[2]</b></sup></sup> в `ACAD-Linetype.xml` при създаване на файлове с прости и сложни типове `линии` (_*.lin_) за AutoCAD
  * **acad-script.xml** - автоматично завършване на наличните команди<sup><sup><b>[2]</b></sup></sup> в `ACAD-Script.xml` за оцветяване при създаване на `скрипт` файлове (_*.scr_) за AutoCAD.

> <sup><sup><b>[1]</b></sup></sup> _При стандартна инсталация, папките на Notepad++, се намират в `C:\Program Files\Notepad++` или `C:\Program Files (x86)\Notepad++`_
>
> <sup><sup><b>[2]</b></sup></sup> _Пълният списък с команди се извежда, чрез натискане на клавиши Ctrl+Space_

**_След извършване на горните промени, е препоръчително Notepad++ да се рестартира_**

---
#### Notepad++
--
You can download Notepad++ from [here](http://notepad-plus-plus.org/)

---
#### Highlight Syntax for AutoCAD
--
The files from folder `userDefineLang` must be imported in Notepad++ by `Language` > `Define your language...` > `Import...`

  * **ACAD-Linetype.xml** - syntax highlight for `linetypes` files (_*.lin_) for AutoCAD
  * **ACAD-Script.xml** - syntax highlight for `script` files (_*.scr_) for AutoCAD
  * **ACAD-Shape-Hatch.xml** - syntax highlight for `shape` files (_*.shp_) and `hatch` types files (_*.pat_) for AutoCAD

> :warning: _Note:_
>
> If you update the existing UDLs, you must remove them firstly because of duplication

--
#### Auto-Completion Functions
--
The files from folder `plugins` > `APIs` must be placed in folder `Notepad++` > `plugins` > `APIs`<sup><sup><b>[1]</b></sup></sup>

You must enable `Auto-Completion` option in Notepad++ from `Setting` > `Preferences` > `Auto-Completion` > `Enable auto-completion on each input` > `Function and word completion`

> :warning: _Note:_
>
> The proper highlight Syntax must be available in Notepad++

  * **acad-linetype.xml** - auto-completion commands<sup><sup><b>[2]</b></sup></sup> for `linetypes` (_*.lin_) for AutoCAD
  * **acad-script.xml** - auto-completion commands<sup><sup><b>[2]</b></sup></sup> for `script` files (_*.scr_) for AutoCAD

> <sup><sup><b>[1]</b></sup></sup> _By default installation the Notepad++ folders are in `C:\Program Files\Notepad++` or `C:\Program Files (x86)\Notepad++`_
>
> <sup><sup><b>[2]</b></sup></sup> _Full list of commands can be displayed by pressing Ctrl+Space_

**_It is recommended to restart Notepad++ after changes_**

---
#### Screenshots
--
* **Hatch (щриховки)**

![Hatch](/images/acad-hatch.png?raw=true)

* **Linetype (типове линии)**

![Linetype](/images/acad-linetype.png?raw=true)

* **Script (скрипт файл)**

![Script](/images/acad-script.png?raw=true)

* **Shape (форма файл)**

![Shape](/images/acad-shape.png?raw=true)
