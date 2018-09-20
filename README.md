## Table of Contents
/* - [Recommended Extras](#recommended-extras)
    - [Administration](#administration)
    - [Commenting & Feedback](#commenting--feedback)
    - [Core Extentions](#core-extentions)
    - [Custom Resource Classes](#custom-resource-classes)
    - [Custom Template Variable Types](#custom-template-variable-types)
    - [Debugging](#debugging)
    - [Development](#development)
    - [Element Synchronization](#element-synchronization)
    - [Extra Development](#extra-development)
    - [General Purpose](#general-purpose)
    - [Rich Text Editor](#rich-text-editor)
- [Contribute](#contribute)
- [Credit](#credit) */

## Дополнения
Note: Extras marked with [!] have to be built manually from source because they are not available from any extra repos.

### Комменты

- [Quip](https://modx.com/extras/package/quip) - A simple commenting system, complete with a backend management interface.

### Core Extentions
*Extentions done to the core functionality of MODX.*

- [modxSmarty](https://modx.com/extras/package/modxsmarty) - Uses MODX-Smarty class and allow to use MODX-tags in Smarty-templates.

### Custom Resource Classes
*Extras that implement custom resource classes.*

- [Collections](https://modx.com/extras/package/collections) - Adds a custom CollectionContainer resource class that hides direct children.
- [Grid Class Key](https://modx.com/extras/package/gridclasskey) - A custom class key to hide child resources inside container's grid.

### Custom Template Variable Types
*Extras that implement new custom TV types.*

- [MIGX](https://modx.com/extras/package/migx) - Custom-tv-input-type for adding multiple items into one TV-value and a snippet for listing this items on your frontend.
- [prism](https://modx.com/extras/package/prism) - Lightweight extra that adds a ColorPicker Input Type to your Template Variables.
- [Image+](https://modx.com/extras/package/imageplustvinput) - Advanced Image custom template variable type, allowing you to crop and resize images without modifying the source. Visual Image cropping tool integrated into the MODX manager interface.
- [DateRangeTV](http://modx.com/extras/package/daterangetv) - Custom template variable with two depending datepicker inputs. Could be used to insert a date range in a MODX resource. 

### Development
*Extras that does development easier.*

- [ElementHelper](https://modx.com/extras/package/elementhelper) - Plugin for automatically creating elements from static files without the MODx manager.
- [modDevTools](https://modx.com/extras/package/moddevtools) - Makes it faster and easier to work in the manager panel.
- [tagElementPlugin](https://modx.com/extras/package/tagelementplugin) - Plugin which allows to edit chunks and snippets selecting their tags in the textarea field of resource, chunk or template forms.
- [UiCMPGenerator](https://modx.com/extras/package/uicmpgenerator) - Generates the xPDO scheme files and xPDO classes for your custom database tables.

### Element Synchronization
*Extras that synchronizes between static files and MODX Elements.*

- [ElementHelper](http://modx.com/extras/package/elementhelper) - Plugin for automatically creating elements from static files without using the manager interface.
- [MODX-Mirror](https://github.com/digitalbutter/MODX-Mirror)[!] - Synchronizes elements (templates, chunks, plugins and snippets) from filesystem with database and reverse.
- [StaticCollector](https://github.com/OptimusCrime/modx-staticcollector)[!] - Extra for easing development with static resources.
- [StaticSaver](http://modx.com/extras/package/staticsaver) - Plugin that automatically sets up the name of file and media source of element (template, chunk, snippet, TV or plugin) when wanting to make this element be static.

### Extra Development
*Extras used to develop other Extras.*

- [MyComponent](http://modx.com/extras/package/mycomponent) - Automates many of the tasks involved in creating a transport package for a Extra.
- [Git-Package-Management](http://theboxer.github.io/Git-Package-Management/installation/) - Manage, develop and package extras from a simple CMP. 
- [generator-bxrextra](https://github.com/theboxer/generator-bxrextra) - A generator to quickly create a basic extra including ExtJS CMP.

### Формы
Nothing here yet.

### Поиск
- [SimpleSearch](https://modx.com/) - поиск по сайту , по ресурсам

### админка
- [filetranslit](https://modx.com/) - Данный плагин транслитерирует название файла из кириллицы в латиницу. Незаменим при переносе сайтов с большим количеством файлов. Помогает избежать ошибок “коверкания” кирилических названий файлов. 
- [Statiker](https://modx.com/) - Statiker is a MODx Revolution Extra that generates static files from resources. 
- [ModTree](https://modstore.pro/packages/ecommerce/modtree) - Компонент позволяет связать ресурсы сайта между собой. На странице связанные ресурсы выводятся в виде дерева.
- [eventsCalendar2](https://modstore.pro/packages/booking/eventscalendar2) - Сниппет вывода ресурсов сайта в виде календаря событий. Может брать дату для вывода из ТВ параметра или свойства ресурса.Отлично подходит для вывода различных встреч, праздников, новостей, событий и т.д.
- [Resource Hider](https://modx.com/extras/package/resourcehider) - Позволяет скрыть дочерние ресурсы

### Редакторы
*Подсветка кода*

- [Ace](http://modx.com/extras/package/ace) - Provides syntax highlighting and desktop-editors behavior (Sublime, Vim, Textmate) in your Elements, Files and Resources.
- [CodeMirror](https://modx.com/extras/package/codemirror) - Custom syntax highlighting in Elements.

*WYSIWIG*

- [TinyMCE Rich Text Editor](https://modx.com/extras/package/tinymcerichtexteditor) - Extra for the TinyMCE RTE.
- [TinymceWrapper](https://modx.com/extras/package/tinymcewrapper) - Wrapper for always latest version of TinyMCE. Also includes image gallery, elFinder etc.
- [Markdown Editor](http://theboxer.github.io/markdown-editor/contributing/) - Markdown редактор для MODX.

### TV
- [ColorPicker](https://modx.com/) - новый тип TV выбор цвета из палитры
- [prism](https://modx.com/extras/package/prism) - аналог ColorPicker
- [DaterangeTV](https://modx.com/extras/package/daterangetv) - новый тип TV дата
- [TV Sorter](https://github.com/meltingmedia/TV-Sorter) - сортировка TV
- [CheckboxSortable ](https://modx.com/extras/package/checkboxsortable) - сортировка чекбоксов 
[github](https://github.com/meltingmedia/checkboxsortable) 

### Быстрое администрирование
- [Group Edit](https://modx.com/extras/package/groupedit) - Групповое редактирование (и создание) ресурсов. Подходит для управления каталогом, новостями и т.п.
Добавлена возможность скрывать подкатегории и товары в дереве документов.
Возможны глючки, т.к. сыровато. Из типов ввода для ТВ пока поддерживается только Картинки. Но есть возможность открыть редактирование в новом окне и там будет как обычно со всеми типами ввода.
- [Asides](https://modx.com/extras/package/asides) - позволяющий вам легко управлять "asides" на веб-сайте, используя куски.
[github](https://github.com/meltingmedia/asides) 


### debug
- [logPageNotFound](https://modx.com/) - Реализует лог 404 ошибок в панели администратора. Очень полезный компонент для отслеживания битых ссылок. Лог реализуется в виде ресурса, снятого с публикации.
- [cacheClear](https://modx.com/) - Компонент позволяет вам полностью очистить папку /core/cache/ одним кликом и будет полезен тем, кто не имеет доступа к FTP или панели хостинга. Также реализуется в виде неопубликованого ресурса.
- [debugParser](https://modstore.pro/packages/utilities/debugparser) -  Позволит отыскать проблемные места на вашем сайте. Добавив некоторые параметры к URL странице на фронтенде, вы увидите листинг, приводящий скорость парсинга каждого чанка или сниппета на странице, а также время и количество запросов к базе данные каждым компонентом.
- [controlErrorLog](https://modstore.pro/packages/utilities/controlerrorlog) -  Очень нужный плагин, который сообщает вам о наличии записей в журнале ошибок MODx без необходимости визита в соответствующее меню, добавляя иконку на панели верхнего меню.
- [Bloodline](https://modx.com/extras/package/bloodline) - Bloodline summarizes all components used to generate a page so you can quickly find the Chunks, Snippets, or TVs responsible for generating a particular part of a page.
- [xBug](https://modx.com/extras/package/xbug) - Utility extra that can be used to profile page loads, xPDOQuery objects, and SQL Queries.

### БЕЗОПАСНОСТЬ
- [easyBlacklist](https://modstore.pro/packages/users/easyblacklist) - простой черный список IP-адресов
- [scannerMODX](https://modstore.pro/packages/utilities/scannermodx) - проверка директорий MODX на вирусы
- [ResourceWatcher](https://modx.com/extras/package/resourcewatcher) - отправляет увемление о созданном или обновленном ресурсе

========================== платные пакеты
SEOSuite - Automatically fix 404 errors on your website
https://en.modstore.pro/packages/ecommerce/seosuite

mSocialVK Постинг VK на основе mSocial
https://modstore.pro/packages/alerts-mailing/msocialvk

tagElementPlugin - Данный компонент позволяет редактировать чанк или сниппет по выделению его тега и нажатию сочетаний клавиш ctrl+enter. Очень удобная штука, только с одним минусом – работает только в редакторе ACE.
https://modstore.pro/packages/utilities/tagelementplugin

ms2GalleryBabelCopying - Копирование файлов ms2Gallery из языковых версий в текущую.
https://modstore.pro/packages/photos-and-files/ms2gallerybabelcopying

ms2guploader - Загрузка изображений с фронтэнда в ms2Gallery.
https://modstore.pro/packages/photos-and-files/ms2guploader

msProfile - Работа с профилями: оплата товаров с внутреннего счета пользователя
https://modstore.pro/packages/users/msprofile

mspQiwi Метод оплаты заказов miniShop2 через Qiwi.
https://modstore.pro/packages/payment-system/mspqiwi

xPoller2 Мультиязычный опрос
https://modstore.pro/packages/other/xpoller2

msGdePosilka Отслеживание посылок через сервис "ГдеПосылка"
https://modstore.pro/packages/integration/msgdeposilka

mSocial Постинг в Twitter
https://modstore.pro/packages/alerts-mailing/msocial

modPNotify Сборщик PNotify для MODX
https://modstore.pro/packages/alerts-mailing/modpnotify

ms2DeliveryCost - Предварительный расчет цены доставки для каждого пункта доставки
Предварительный расчет цены доставки для каждого пункта доставки

mspRobokassa - Метод оплаты заказов miniShop2 через Robokassa.
https://modstore.pro/packages/payment-system/msprobokassa

Formz - позволяет получить формы и работает на вашем сайте. Храните информацию в базе данных или отправляйте оповещения по электронной почте.
https://extras.io/extras/formz/

ModLab - тепловая карта для менеджера
https://extras.io/extras/modlab/

MySQL Caching - Кэширование базы данных для MODX
https://extras.io/extras/mysqlcaching/

Blockdown
https://www.modmore.com/extras/

SimpleAB - позволяет A / B (split) тестировать блоки и шаблоны в MODX.
https://www.modmore.com/extras/simpleab/

Scheduler - предназначен для обеспечения простой интеграции и администрирования механизма планирования или очереди сообщений для разработчиков с компонентом для администраторов.
https://www.modmore.com/extras/scheduler/

Gitify Watch - Дополнение к инструменту командной строки Gitify, Gitify Watch-это плагин, установленный в MODX, который автоматически извлекает и фиксирует изменения в вашем репозитории git.
https://www.modmore.com/gitifywatch/

oEmbed - С пакетом oEmbed у вас есть новый тип ввода для ContentBlocks, который позволяет легко вставлять ссылки с поддержкой oEmbed.
https://docs.modmore.com/en/ContentBlocks/v1.x/Custom_Inputs/Third_Party_Input_Types.html#jump_oembed_input

Blockdown - редактор Markdown типа для ContentBlocks используя EpicEditor.
https://docs.modmore.com/en/ContentBlocks/v1.x/Custom_Inputs/Third_Party_Input_Types.html#jump_blockdown_(by_john-paul_devries)

HandyMan - Редактирование контента специально для мобильных устройств, построенное на jQuery Mobile.

Quickstart Buttons - быстрые кнопки в админке
https://www.modmore.com/extras/quickstartbuttons/


========================== 

Bloodline - Bloodline summarizes all components used to generate a page so you can quickly find the Chunks, Snippets, or TVs responsible for generating a particular part of a page.
https://modx.com/extras/package/bloodline

controlErrorLog - Error log in a popup in the manager views. Email notification about changes in the error log.
https://modx.com/extras/package/controlerrorlog

xBug - Utility extra that can be used to profile page loads, xPDOQuery objects, and SQL Queries.
https://modx.com/extras/package/xbug

debugParser - Component that will show you slow tags on webpage.
https://modx.com/extras/package/debugparser
