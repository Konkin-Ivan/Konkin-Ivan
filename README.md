[![banner](https://raw.githubusercontent.com/Konkin-Ivan/Konkin-Ivan/main/files/banner.gif)](https://konkin.info)

Привет, меня зовут Иван.

#### Любимые предметные области:
- парсинг данных;
- торговые боты и алгоритмы для трейдинга;

#### Обладаю:
- уверенными знаниями языка PHP 7+ и PHP 8+;
- знаниями и опытом применения стандартов PSR;
- владением Composer, Linux системой, Git, Docker;
- уверенными знаниями HTML, CSS, JS, сетевого слоя, SQL, архитектуры MVC, принципов SOLID и паттернов;
- знаниями принципов безопасности работы приложений и пользовательских данных;
- опытом эффективного построения REST API, оптимизации кода и нахождения оптимальных и эффективных способов решения задач.

#### Читаю книги:

- "Филоссофия Java" - по моему мнению, эта книга луше всех объясняет объекты.
- "Код. Тайный язык информатики" — научно-популярная книга американского программиста Чарльза Петцольда, в которой рассказывается, как персональные компьютеры работают на аппаратном и программном уровне.
- "Грокаем алгоритмы". Алгоритмы - это всего лишь пошаговые инструкции решения задач, и большинство таких задач уже были кем-то решены, протестированы и проверены.
- "Автоматное программирование" — это парадигма программирования, при использовании которой программа или её фрагмент осмысливается как модель какого-либо формального автомата.
- "Цель. Процесс непрерывного совершенствования". Голдратт Элияху рассказывает о том, как научиться управлять тем, что происходит, как понимать это. Книга построена в формате производственного романа, но главное в ней не сюжет, а методология и советы. Просто в таком контексте информация усваивается лучше и без труда.

---

### ⚙️ GitHub статистика:

<table>
  <tr>
    <td>
      <img align="left" src="https://github-readme-streak-stats.herokuapp.com/?user=konkin-ivan&theme=dark&background=000000" alt="webDev's Github stats" />
    </td>
    <td>
      <img height="195px" align="right" alt="webDev's Github Languages" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=konkin-ivan&layout=compact&theme=vision-friendly-dark" />
    </td>
  </tr>
</table>

### 💻 Codewars:

![codewars](https://www.codewars.com/users/konkin/badges/large)

### 💻 LeetCode:

![Konkin LeetCode stats](https://leetcode-stats-six.vercel.app/api?username=user1034qO&theme=dark)

---

### 💻 Технологии:
<!-- ![JavaScript](https://img.shields.io/badge/-JavaScript-090909?style=for-the-badge&logo=JavaScript) -->
<!-- ![css](https://img.shields.io/badge/-CSS3-090909?style=for-the-badge&logo=css3) -->
<!-- ![less](https://img.shields.io/badge/-LESS-090909?style=for-the-badge&logo=less) -->
<!-- ![gulp](https://img.shields.io/badge/-GULP-090909?style=for-the-badge&logo=gulp) -->
<!-- ![html](https://img.shields.io/badge/-HTML5-090909?style=for-the-badge&logo=html5) -->
![php7.0+](https://img.shields.io/badge/-PHP-090909?style=for-the-badge&logo=php)
![laravel](https://img.shields.io/badge/-Laravel-090909?style=for-the-badge&logo=laravel)
![Symfony](https://img.shields.io/badge/-Symfony-090909?style=for-the-badge&logo=symfony)
<!-- ![Yii](https://img.shields.io/badge/-Yii-090909?style=for-the-badge&logo=yii) -->


---

### 🤝 Социальные сети:
[![telegram](https://img.shields.io/badge/-Telegram-090909?style=for-the-badge&logo=telegram)](https://t.me/konkin_ivan)
[![vk](https://img.shields.io/badge/-ВКонтакте-090909?style=for-the-badge&logo=vk)](https://vk.com/konkin_ivan)
[![stackoverflow](https://img.shields.io/badge/-Stackoverflow-090909?style=for-the-badge&logo=stackoverflow)](https://ru.stackoverflow.com/users/272147/%d0%98%d0%b2%d0%b0%d0%bd-%d0%9a%d0%be%d0%bd%d0%ba%d0%b8%d0%bd)

---

## Избранное

[API для CRUD на Symfony 6](https://github.com/Konkin-Ivan/crud_api)

Реализовать на symfony (5 или 6 версия) API для CRUD операций над пользователем.
Таблица пользователей содежит следующие поля: id, email, name, age, sex, birthday, phone, created_at, updated_at.
При реализации необходимо сделать валидацию для всех передаваемых полей.
Код оформить по PSR стандартам.
По выполнению задания:
- написать инструкцию по разворачиванию проекта
- залить код на github
- будет плюсом докеризация приложения
- наличие сервисного слоя обязательно

[Модуль расчета стоимости доставки](https://github.com/Konkin-Ivan/test_task_for_Intelogis)

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

---

![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=konkin-ivan&theme=solarized_dark)

---

Мой блог: [program-mister.ru](https://program-mister.ru)

![](https://komarev.com/ghpvc/?username=konkin-ivan)