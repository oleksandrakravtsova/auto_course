## HTML. Форми

<details open>
  <summary>Теорія</summary>

#### `type="radio"` .

Щоб отримати від користувача тільки одну відповідь з запропонованих нами варіантів, у формі використовуються поля з так званими перемикачами. За такі перемикачі відповідає атрибут `type="radio"` тегу `input`. 

Приклад:

```html
<form>
    <label>
        HTML
       <input type="radio" name="mark-html">
    </label>
        <label>
        CSS
       <input type="radio" name="mark-css">
    </label>
    <label>
        JavaScript
       <input type="radio" name="mark-js">
    </label>
</form>
```

У браузері це виглядатиме наступним чином:

<div class="browser">
<form>
    <label>
        HTML
       <input type="radio" name="mark-html">
    </label>
        <label>
        CSS
       <input type="radio" name="mark-css">
    </label>
    <label>
        JavaScript
       <input type="radio" name="mark-js">
    </label>
</form>
</div>

</details>

<h3 class="task">Завдання</h3>

Створіть свою форму, яка матиме 3 поля з перемикачами.

<h3 class="test">Критерії виконання завдання</h3>

- Код повинен містити тег `form`, `input` необхідного типу та `label`.
- Інших тегів, крім них не повинно бути.


