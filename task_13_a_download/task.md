## HTML. Атрибути посилання

<details open>
  <summary>Теорія</summary>

#### Атрибут `download`.

Для того, щоб завантажити файл з веб-сторінки використовують тег посилання, але обов'язково з атрибутом `download.` Цей атрибут дозволяє зрозуміти браузеру, що замість того, щоб переходити за посиланням, йому необхідно виконати процедуру завантаження. В атрибуті `href` пишемо шлях до нашого файлу. 

Приклад:

```html
<a href="car.jpg" download>Завантажити зображення</a>
```
У браузері це виглядатиме наступним чином:

<div class="browser">
<a href="car.jpg" download>Завантажити зображення</a>
</div>

</details>

<h3 class="task">Завдання</h3>

Створіть посилання для завантаження макету сайту.

<h3 class="test">Критерії виконання завдання</h3>

- Код повинен містити тег `a` з атрибутом `download`.
- Тег не повинен бути пустим.
- Інших тегів, крім `a` не повинно бути.