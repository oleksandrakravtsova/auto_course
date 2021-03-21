## HTML. Списки `ol` та `ul`

<details open>
<summary>Теорія</summary>

#### `ol`, `ul` та `li`

Якщо треба щось перелічити, то заголовки, або параграф не дуже підходять. 
Тому використовують геть інші теги - упорядкований `ol` та неупорядкований список `ul`.
Єдиним нащадком цих елементів повинен бути тег `li`

Якщо є потреба зазначати відношення до порядку - що повинно бути першим, а що другим, використовують упорядкований список.
Наприклад, список з мовами програмування:

```html
<ol>
  <li>JavaScript</li>
  <li>Python</li>
  <li>Java</li>
</ol>
```

<div class="browser">
  <ol>
    <li>JavaScript</li>
    <li>Python</li>
    <li>Java</li>
  </ol>
</div>

Але якщо бажаєте просто перелічити мови, не зважаючи на те, у якому порядку вони йдуть, то використовують неупорядкований список `ul`.

```html
<ul>
  <li>JavaScript</li>
  <li>Python</li>
  <li>Java</li>
</ul>
```

<div class="browser">
  <ul>
    <li>JavaScript</li>
    <li>Python</li>
    <li>Java</li>
  </ul>
</div>

</details>

<h3 class="task">Завдання</h3>

За допомогою тегів `ul` та `ol` створіть два списки, кожен з яких міститиме `три` послуги, які надає ваша компанія. 


<h3 class="test">Критерії виконання завдання</h3>

- Код повинен містити тег `ol` з тегом `li`.
- Код повинен містити тег `ul` з тегом `li`.
- Інших тегів в тексті бути не повинно.