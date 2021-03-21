## HTML. Форми

<details open>
  <summary>Теорія</summary>

#### `type="checkbox"` .

У деяких випадках нам потрібно отримати від користувача одну або більше відповідей з запропонованих нами варіантів. Для цього використовуються поля з прапорцями, а у коді за них відповідає атрибут `type="checkbox"` тегу `input`. 

Приклад:

```html
<form>
    <label>
        HTML
       <input type="checkbox" name="mark-html">
    </label>
        <label>
        CSS
       <input type="checkbox" name="mark-css">
    </label>
    <label>
        JavaScript
       <input type="checkbox" name="mark-js">
    </label>
</form>
```

У браузері це виглядатиме наступним чином:

<div class="browser">
<form>
    <label>
        HTML
       <input type="checkbox" name="mark-html">
    </label>
        <label>
        CSS
       <input type="checkbox" name="mark-css">
    </label>
    <label>
        JavaScript
       <input type="checkbox" name="mark-js">
    </label>
</form>
</div>

</details>

<h3 class="task">Завдання</h3>

Створіть свою форму, яка матиме 3 поля з прапорцями.

<h3 class="test">Критерії виконання завдання</h3>

- Код повинен містити тег `form`, `input` необхідного типу та `label`.
- Інших тегів, крім них не повинно бути.


