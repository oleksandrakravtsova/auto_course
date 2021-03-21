## HTML. Форми

<details open>
  <summary>Теорія</summary>

#### `type="submit"` .

Атрибут `type="submit"` для тегу `input` буде створювати у браузері кнопку для відправки форми. 

Приклад:

```html
<form>
 <input type="submit"  name="btn">
</form>
```

У браузері це виглядатиме наступним чином:

<div class="browser">
<form>
 <input type="submit"  name="btn">
</form>
</div>

Щоб замінити текст в середині кнопки, необхідно використати атрибут `value` з необхідним текстом.

Приклад:

```html
<form>
 <input type="submit"  name="btn" value="Надіслати">
</form>
```
У браузері це виглядатиме наступним чином:

<div class="browser">
<form>
 <input type="submit"  name="btn" value="Надіслати">
</form>
</div>

</details>

<h3 class="task">Завдання</h3>

Створіть форму, яка матиме два поля: логін і пароль, в які користувач буде вводити свої дані, і кнопку "Увійти".

<h3 class="test">Критерії виконання завдання</h3>

- Код повинен містити тег `form`, `input` необхідного типу  та `label`.
- Інших тегів, крім них не повинно бути.


