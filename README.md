<!---
[![banner](https://raw.githubusercontent.com/Konkin-Ivan/Konkin-Ivan/main/files/banner.gif)](https://konkin.info)
-->

## Технологии с которыми работаю:
<!-- ![JavaScript](https://img.shields.io/badge/-JavaScript-090909?style=for-the-badge&logo=JavaScript) -->
<!-- ![css](https://img.shields.io/badge/-CSS3-090909?style=for-the-badge&logo=css3) -->
<!-- ![less](https://img.shields.io/badge/-LESS-090909?style=for-the-badge&logo=less) -->
<!-- ![gulp](https://img.shields.io/badge/-GULP-090909?style=for-the-badge&logo=gulp) -->
<!-- ![html](https://img.shields.io/badge/-HTML5-090909?style=for-the-badge&logo=html5) -->
![php7.0+](https://img.shields.io/badge/-PHP-090909?style=for-the-badge&logo=php)
![laravel](https://img.shields.io/badge/-Laravel-090909?style=for-the-badge&logo=laravel)
![Yii2](https://img.shields.io/badge/-Yii2-090909?style=for-the-badge&logo=yii2)
![Symfony](https://img.shields.io/badge/-Symfony-090909?style=for-the-badge&logo=symfony)

## Избранное

[Тестовое задание для Intelogis: "модуль расчета стоимости доставки"](https://github.com/Konkin-Ivan/test_task_for_Intelogis)

Требуется спроектировать модуль расчета стоимости доставки.
Есть две службы доставки:

1. «Быстрая доставка»:
```
base_url: string
@var sourceKladr string //кладр откуда везем
@var targetKladr string //кладр куда везем
@var weight float //вес отправления в кг
@return json
{
    'price': float //стоимость
    'period': int //количество дней начиная с сегодняшнего, но после 18.00
заявки не принимаются.
    'error': string
}
```
2. «Медленная доставка»:
имеет базовую стоимость 150р
```
base_url: string
@var sourceKladr string //кладр откуда везем
@var targetKladr string //кладр куда везем
@var weight float //вес отправления в кг
@return json
{
    'coefficient': float //коэффициент (конечная цена есть произведение
базовой стоимости и коэффициента)
    'date': string //дата доставки в формате 2017-10-20
    'error': string
}
```
Задача в том, чтобы получить для набора отправлений стоимость и сроки
доставки в контексте списка транспортных компаний и одной выбранной. Формат
полученных от транспортных компаний данных должен быть приведен к единому
виду 
```
(
    {
        'price': float //стоимость
        'date': string //дата доставки в формате 2017-10-20
       'error': string
    }
)
```
.

[Message_queues (сообщения очереди) Laravel](https://github.com/Konkin-Ivan/message_queues)

Система по приему заявок на создание/регистрацию пользователей от любых систем по протоколу HTTP. Система должна состоять из двух основных модулей. Задача первого модуля - принимать заявки на создание пользователей и передавать их на асинхронное исполнение второму модулю через встроенный брокер очередей Laravel и отвечать инициатору создания в синхронном режиме только после того как пользователь будет создан. Задача второго модуля - принимать сообщения-заявки из очереди - и создавать пользователя в реляционной БД.

[Custom_mvc_php (без ООП) чистый PHP](https://github.com/Konkin-Ivan/custom_mvc_php)

Приложение построенное по принципам MVC-архитектуры, без использования ООП. На этой системе я изучал принципы организации кода, сходные с фреймворками и састемами управления контента, но в упрощенном виде.

Реализованы следующие функции:

* полноценный роутинг;
* отдельные шаблоны для вывода контента;
* контроллеры;
* REST API;
* Docker.

[Игры разума (без ООП) чистый PHP](https://github.com/Konkin-Ivan/php-project-lvl1)

Программа из четырех логических игр, построенных на элементарной арифметической логике. (вычислить выражение, четное или нет число, наименьший общий делитель, недостающее число прогрессии). У всех игр сходная логика, за небольшим исключением.

Был применен подход единственной ответственности (из принципов SOLID). Где, общая логика вычислений вынесена в ядро (движок игры), в который передаются данные из разных игр на обработку.

Проект является курсовым, по результатам прохождения основ программирования.

[Функции высшего порядка (собственная реализация) PHP](https://github.com/Konkin-Ivan/higher_order_functions)

Функции высшего порядка являются основными и не заменимыми в большенестве программ. Для детального понимания механизма работы этих функций, были сделаны собственные реализации.

* array_filter
* array_map
* array_reduce

[Durk-Light-site-colorscheme (переключатель тем) JS](https://github.com/Konkin-Ivan/Durk-Light-site-colorscheme)

Работает с псевдоэлементом "checked" (который прописан в CSS). Состояние "checked" хранится в "localStorage" браузера. В зависимости от значения кнопки подключается дневной или ночной стиль оформления.

[Fuzz-Buzz JS](https://github.com/Konkin-Ivan/Fuzz-Buzz)

Программа, которая выводит на экран числа от 1 до 100. При этом вместо чисел, кратных трем, программа должна выводить слово «Fizz», а вместо чисел, кратных пяти — слово «Buzz». Если число кратно и 3, и 5, то программа должна выводить слово «FizzBuzz».

[Roman-and-arabic-calc (первый в моей жизни код) JS](https://github.com/Konkin-Ivan/roman-and-arabic-calc)

Калькулятор, который умеет вычислять как Арабские, так и Римские цифры. Это первая программа, которую я попытался реализовать. Код очень плох, но я им горжусь.

### Я здесь:
[![telegram](https://img.shields.io/badge/-Telegram-090909?style=for-the-badge&logo=telegram)](https://t.me/konkin_ivan)
[![vk](https://img.shields.io/badge/-ВКонтакте-090909?style=for-the-badge&logo=vk)](https://vk.com/konkin_ivan)
[![stackoverflow](https://img.shields.io/badge/-Stackoverflow-090909?style=for-the-badge&logo=stackoverflow)](https://ru.stackoverflow.com/users/272147/%d0%98%d0%b2%d0%b0%d0%bd-%d0%9a%d0%be%d0%bd%d0%ba%d0%b8%d0%bd)

Мой блог: [program-mister.ru](https://program-mister.ru)
