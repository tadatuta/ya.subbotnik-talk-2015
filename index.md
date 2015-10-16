---

layout: default

---

# Яндекс

## **{{ site.presentation.title }}** {#cover}

<div class="s">
    <div class="service">{{ site.presentation.service }}</div>
</div>

{% if site.presentation.nda %}
<div class="nda"></div>
{% endif %}

<div class="info">
	<p class="author">{{ site.author.name }}, <br/> {{ site.author.position }}</p>
</div>

## Поговорим
* bem-components
* ...её составе
* ...особенностях
* ...способах использования
* ...и сравним с Bootstrap

## **Компонентный подход — это модно**

## Компонентный подход
* Web Components
* ...React

## **Библиотеки компонент —<br>это молодежно**

## Библиотеки готовых компонент
* Polymer / X-Tag
* ...react-components
* ...Material Design Light

## **Bootstrap**

## **Мы делали универсальные компоненты, когда это еще не было мейнстримом**

## ![](pictures/hipsters.jpg)
{:.cover .w}

## **Мурся, с Днем рождения! #твитдлямурси #yasubbotnik**

## &nbsp;
{:.section}

### bem-components

## **[Demo](http://tadatuta.github.io/bem-components-demo/)**

## **[Showcase](https://ru.bem.info/libs/bem-components/current/showcase/)**

## bem-components
{:.section}

### Особенности

## Особенности
* Построена по БЭМ-методологии

## **[Например](http://jsfiddle.net/tadatuta/momLtmn9/)**
## **[bit.ly/boostrap-telega](http://bit.ly/boostrap-telega)**

## Особенности
* Построена по БЭМ-методологии
* Тема опциональна

## **[Boostrap](http://jsfiddle.net/tadatuta/hb2ehqde/)**

## Особенности
* Построена по БЭМ-методологии
* Тема опциональна
* Кроссплатформенность
* ...Проработана доступность

## **[Boostrap](http://jsfiddle.net/tadatuta/mmoee4x6/)**
## **[bem-components](http://jsfiddle.net/tadatuta/pphg7bgg/)**

## **[Boostrap](http://getbootstrap.com/css/#selects)**
## **[bem-components](https://ru.bem.info/libs/bem-components/v2.3.0/desktop/select/)**

## Особенности
* Построена по БЭМ-методологии
* Тема опциональна
* Кроссплатформенность
* Проработана доступность
* Декларативные шаблоны (опционально)

## **[Шаблоны на клиенте](http://jsfiddle.net/tadatuta/h307ayjc/)**

## Особенности
* Построена по БЭМ-методологии
* Тема опциональна
* Кроссплатформенность
* Проработана доступность
* Декларативные шаблоны (опционально)
* Декларативный JS

## Недостатки
* Полнота
* ...Объем кода
* ...Меньше пользователей
* ...«Меньше артефактов»

## Тесты
* Unit-тесты на JS
* ...Тесты на шаблоны
* ...Тесты на верстку (gemini)
* ...Линтеры
* ...CI

## bem-components
{:.section}

### Использование

## Использование
* Dist
    * ...Подключение с CDN
    * ...bower / npm
    * ...Скачать архив
* ...Собирать собственную сборку
* ...Предкомпилированная версия
* ...Собрать из исходников

## Подключение с CDN
~~~ javascript
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="https://yastatic.net/bem-components/latest/desktop/bem-components.css">
</head>
<body>

    <script src="https://yastatic.net/bem-components/latest/desktop/bem-components.js+bemhtml.js"></script>
</body>
</html>
~~~

## Пакетные менеджеры
{:.code-with-text}

### bower
~~~ javascript
bower i bem-components-dist
~~~

### npm
{:.next}

{:.next}
~~~ javascript
npm i bem-components-dist
~~~

### Скачать
{:.next}

...[github.com/bem/bem-components-dist/archive/v2.3.0.zip](https://github.com/bem/bem-components-dist/archive/v2.3.0.zip)

## **[Используем блоки](http://jsfiddle.net/)**

## Резюмируя вышесказанное
* bem-components — качественная библиотека готовых компонент
* ...её очень легко использовать

## **Контакты** {#contacts}

<div class="info">
<p class="author">{{ site.author.name }}</p>
<p class="position">{{ site.author.position }}</p>

    <div class="contacts">
        <p class="contacts-left contacts-top">bem.info/libs/bem-components</p>
        <p class="contacts-left mail">info@bem.info</p>
        <p class="contacts-right twitter">bem_ru #b_</p>
        <!-- <p class="contacts-right contacts-bottom vk">vk</p> -->
        <!-- <p class="contacts-right facebook">facebook</p> -->
    </div>
</div>
