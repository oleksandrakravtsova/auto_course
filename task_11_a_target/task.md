## HTML. Атрибути посилання

<details open>
  <summary>Теорія</summary>


#### Посилання. Атрибут `target`.

 Де саме браузер відкриє сторінку за посиланням (у цьому вікні або у наступній вкладці) залежить від атрибуту `target`.

-   у наступній вкладці: `target="_blank"`
-   у цьому вікні:  це значення за замовчуванням, тому його не обов'язково вказувати. 


#### Правила безпеки. Атрибут `rel`

<div class="attention">
  <h5>Увага</h5>
  <p>
Використовуючи <code>target</code>, ви повинні додавати <code>rel= "nofollow noopener noreferrer"`</code>, щоб уникнути зв'язку з попереднім вікном. Таким чином серфінг стає безпечнішим. 
</p>
</div>

```html
<a href="https://goit.ua/"
   target="_blank"
   rel= "nofollow 
         noopener 
         noreferrer
  ">
  GOIT
</a>
```

<div class="browser">
<a href="https://goit.ua/"
   target="_blank"
   rel= "nofollow 
         noopener 
         noreferrer
  ">
  GOIT
</a>
</div>

</details>

<h3 class="task">Завдання</h3>

Надайте значення `_blank` та `nofollow noopener noreferrer` атрибутам `target` та `rel` у тегу посилання.

<h3 class="test">Критерії виконання завдання</h3>

- Код повинен містить тег `a`.
- Атрибут тегів `target` має значення `_blank`.
- Атрибут тегів `rel` має значення `nofollow noopener noreferrer`.
- Інших тегів в тексті не повинно бути.