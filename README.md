# Список проверок веб-приложения Parkonaf версия MVP

<details>
<summary>Требования к MVP </summary>

***

</details>

На основании требований и макетов, командой QA были составлены чек-листы проверок пользовательского интерфейса, логики работы и валидации полей ввода веб-приложения. 

> **Окружения:** 
> 1. ОС: Windows 10 Pro (версия 22H2) Браузер: Google Chrome Версия: 116.0.5845.97 Разрешение 1920х1080
> 2. ОС: Windows 10 Pro (версия 22H2) Браузер: Яндекс.Браузер Версия: 23.7.1.1140 Разрешение 1920х1080 
> 3. ОС: MacOS Monterey (версия 12.6.8) Браузер: Safari (версия 16.6) Разрешение 1920х1080

# Чек-лист проверок пользовательского интерфейса

<details>
<summary> 1) Главная страница сайта: неавторизованного пользователя</summary>


| № | Описание проверки| Статус Окружение 1| Ссылка Баг-репорт| Статус Окружение 2| Ссылка Баг-репорт| Статус Окружение 3| Ссылка Баг-репорт|
|:-:|:-----------------|:-----------------:|:----------------:|:-----------------:|:----------------:|:-----------------:|:----------------:|
|1  |В левом верхнем углу находятся: - логотип; - строка поиска|PASSED||PASSED||PASSED||
|2  |В правом верхнем углу находятся панель с: - информация "О продукте"; - e-mail parkonaft@gmail.com; - кнопка "Вход"|PASSED||PASSED||PASSED||
|3| Логотип имеет вид буквы Р в квадрате со скругленными углами|PASSED||PASSED||PASSED||
|4|Логотип занимает область 48х48|PASSED||PASSED||PASSED||
|5|Рамка логотипа выполнена цветом #218BEE (Синий)|PASSED||PASSED||PASSED||
|6|Значок логотипа выполнен цветом #3C4158 (Черный)|PASSED||PASSED||PASSED||
|7|Строка поиска находится правее от логотипа на одной линии|PASSED||PASSED||PASSED||
|8|Строка поиска имеет закругленные углы|PASSED||PASSED||PASSED||
|9|Строка поиска имеет размер 442х48|PASSED||PASSED||PASSED||
|10|Строка поиска имеет цвет #FFFFFF (Белый)|PASSED||PASSED||PASSED||
|11|"В строке поиска находят: - лупа (символ поиска); - плейсхолдер ""Название улицы или № парковки"|PASSED||PASSED||PASSED||
|12|Лупа имеет размер 24х24|PASSED||PASSED||PASSED||
|13|Лупа имеет цвет #878787 (Серый)|PASSED||PASSED||PASSED||
|14|Плейсхолдер имеет текст, выполненный шрифтом Raleway, 24рх и цветом #878787|PASSED||PASSED||PASSED||
|15|Текст плейсхолдера не содержит орфографических ошибок|PASSED||PASSED||PASSED||
|16|Выпадающий список из строки поиска имеет закругленные углы снизу|PASSED||PASSED||PASSED||
|17|Выпадающий список из строки поиска имеет размер 442px на 76px (1 адрес в списке)|PASSED||PASSED||PASSED|| 
|18|Выпадающий список из строки поиска имеет цвет в неактивной зоне выбора #FFFFFF (Белый)|PASSED||PASSED||PASSED||
|19|Выпадающий список из строки поиска имеет цвет в активной зоне выбора GrayLight (Светло-серый)|PASSED||PASSED||PASSED||
|20|Текст внутри выпадающего списка строки поиска имеет шрифт Raleway, 24px цвет #191C30|FAILED|[BUG-2](https://github.com/car-parking-tracking/Bug-Report/issues/2)|FAILED|[BUG-2](https://github.com/car-parking-tracking/Bug-Report/issues/2)|FAILED|[BUG-2](https://github.com/car-parking-tracking/Bug-Report/issues/2)|
|21|Текст внутри выпадающего списка строки поиска не имеет орфографических ошибок|PASSED||PASSED||PASSED||
|22|Панель имеет внизу закругленные углы|PASSED||PASSED||PASSED||
|23|Панель имеет размер 416х64|PASSED||PASSED||PASSED||
|24|Панель имеет цвет #3C4158 и прозрачность 80%|PASSED||PASSED||PASSED||
|25|Текст "О продукте" в не активном состоянии выполнен шрифтом Raleway, 16рх и цветом #FFFFFF (Белый)|PASSED||PASSED||PASSED||
|26|Текст "О продукте" при наведении курсора имеет цвет (Синий)|PASSED||PASSED||PASSED||
|27|Текст e-mail "parkonaft@gmail.com" в не активном состоянии выполнен шрифтом Raleway, 16рх и цветом #FFFFFF (Белый)|PASSED||PASSED||PASSED||
|28|Текст e-mail "parkonaft@gmail.com" при наведении курсора имеет цвет (Синий)|PASSED||PASSED||PASSED||
|29|Кнопка "Вход" имеет закругленные углы|PASSED||PASSED||PASSED||
|30|Кнопка "Вход" имеет размер 71х48|PASSED||PASSED||PASSED||
|31|Кнопка "Вход" в не активном состоянии имеет цвет #878787 (Серый)|PASSED||PASSED||PASSED||
|32|Кнопка "Вход" при наведении курсора имеет цвет (Синий)|PASSED||PASSED||PASSED||
|33|Текст кнопки "Вход" выполнен шрифтом Raleway, 16рх и цветом #FFFFFF|PASSED||PASSED||PASSED||

***

</details>

<details>
<summary> 2) Главная страница: просмотр парковок</summary>

| № | Описание проверки| Статус Окружение 1| Ссылка Баг-репорт| Статус Окружение 2| Ссылка Баг-репорт| Статус Окружение 3| Ссылка Баг-репорт|
|:-:|:-----------------|:-----------------:|:----------------:|:-----------------:|:----------------:|:-----------------:|:----------------:|
|34|На увеличенном масштабе карты видны маркеры парковок||PASSED||PASSED||PASSED||
|35|Маркер имеет вид: круг|PASSED||PASSED||PASSED||
|36|Маркер имеет 2 цвета: внешняя часть "голубой" внутренняя заливка "белый"|PASSED||PASSED||PASSED||
|37|Маркер имеет внутри цифру|PASSED||PASSED||PASSED||
|38|Значок парковки на карте выглядит как метка с буквой Р голубого цвета|PASSED||PASSED||PASSED||
|39|Значок парковки имеет размер 34х34|SKIPPED||SKIPPED||SKIPPED||
|40|Значок парковки имеет цвета #5558FF и #FFFFFF|SKIPPED||SKIPPED||SKIPPED||
|41|Значок выбранной парковки на карте выглядит как метка с буквой Р голубого цвета|PASSED||PASSED||PASSED||
|42|Значок выбранной парковки имеет размер 34х34|SKIPPED||SKIPPED||SKIPPED||
|43|Значок выбранной парковки имеет цвета #FF2121 и #FFFFFF|SKIPPED||SKIPPED||SKIPPED||

***

</details>

<details>
<summary> 3) Главная страница: карточка информации о парковки</summary>

| № | Описание проверки| Статус Окружение 1| Ссылка Баг-репорт| Статус Окружение 2| Ссылка Баг-репорт| Статус Окружение 3| Ссылка Баг-репорт|
|:-:|:-----------------|:-----------------:|:----------------:|:-----------------:|:----------------:|:-----------------:|:----------------:|
|44| "Карточка информации содержит:- парковка №; - адрес; - цена за час; - мест свободно; - мест всего; - кнопку "Добавить в избранное"|PASSED||PASSED||PASSED||
|45|Карточка информации имеет закругленные углы|PASSED||PASSED||PASSED||
|46|Карточка информации имеет размер 283х313|PASSED||PASSED||PASSED||
|47|Каточка информации имеет цвет #FFFFFF (Белый)|PASSED||PASSED||PASSED||
|48|Заголовок парковки выполнен шрифтом Raleway, 20рх и цветом #000000|PASSED||PASSED||PASSED||
|49|"Адрес" выполнен шрифтом Raleway, 14рх и цветом #878787 (Серый)|FAILED|[BUG-1](https://github.com/car-parking-tracking/Bug-Report/issues/1)|PASSED||FAILED|[BUG-1](https://github.com/car-parking-tracking/Bug-Report/issues/1)|
|50|Текст адреса выполнен шрифтом Raleway, 16рх и цветом #000000 (Чёрный)|FAILED|[BUG-12](https://github.com/car-parking-tracking/Bug-Report/issues/12)|PASSED||FAILED|[BUG-12](https://github.com/car-parking-tracking/Bug-Report/issues/12)|
|51|"Цена за час" выполнен шрифтом Raleway, 14рх и цветом #878787 (Серый)|FAILED|[BUG-7](https://github.com/car-parking-tracking/Bug-Report/issues/7)|PASSED||FAILED|[BUG-7](https://github.com/car-parking-tracking/Bug-Report/issues/7)|
|52|Текст стоимости выполнен шрифтом Raleway, 16рх и цветом #000000 (Чёрный)|FAILED|[BUG-13](https://github.com/car-parking-tracking/Bug-Report/issues/13)|PASSED||FAILED|[BUG-13](https://github.com/car-parking-tracking/Bug-Report/issues/13)|
|53|Валюта обозначена символом ₽|SKIPPED||SKIPPED||SKIPPED||
|54|"Мест свободно" выполнен шрифтом Raleway, 14рх и цветом #878787 (Серый)|FAILED|[BUG-8](https://github.com/car-parking-tracking/Bug-Report/issues/8)|PASSED||FAILED|[BUG-8](https://github.com/car-parking-tracking/Bug-Report/issues/8)|
|55|Текст количества свободных мест выполнен шрифтом Raleway, 16рх и цветом #000000 (Чёрный)|FAILED|[BUG-14](https://github.com/car-parking-tracking/Bug-Report/issues/14)|PASSED||FAILED|[BUG-14](https://github.com/car-parking-tracking/Bug-Report/issues/14)|
|56|"Мест всего" выполнен шрифтом Raleway, 14рх и цветом 878787 (Серый)|FAILED|[BUG-9](https://github.com/car-parking-tracking/Bug-Report/issues/9)|PASSED||FAILED|[BUG-9](https://github.com/car-parking-tracking/Bug-Report/issues/9)|
|57|Текст количества мест всего выполнен шрифтом Raleway, 16рх и цветом #000000 (Чёрный)|FAILED|[BUG-15](https://github.com/car-parking-tracking/Bug-Report/issues/15)|PASSED||FAILED|[BUG-15](https://github.com/car-parking-tracking/Bug-Report/issues/15)|
|58|Кнопка "Добавить в избранное" имеет закругленные углы|PASSED||PASSED||PASSED||
|59|Кнопка "Добавить в избранное" имеет размер 243х48|PASSED||PASSED||PASSED||
|60|Кнопка "Добавить в избранное" в не активном состоянии имеет цвет #218BEE (Светло-синий)|PASSED||PASSED||PASSED||
|61|Кнопка "Добавить в избранное" при наведении курсора имеет цвет (Тёмно-синий)|PASSED||PASSED||PASSED||
|62|Кнопка "Добавить в избранное" имеет текст, выполненный шрифтом  Raleway, 14рх и цветом #FFFFFF|PASSED||PASSED||PASSED||
|63|Кнопка "Добавить в избранное" имеет значок ♡ справа от текста|PASSED||PASSED||PASSED||
|64|Значок ♡ имеет размеры 20х20|PASSED||PASSED||PASSED||
|65|Значок ♡ имеет линию толщиной 2 и цветом #FFFFFF|PASSED||PASSED||PASSED||
|66|Карточка информации не содержит орфографических ошибок|PASSED||PASSED||PASSED||

***

</details>
