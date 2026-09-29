<p align="center"><img src="logo.svg" alt="" width="96" height="96"></p>

<h1 align="center">Loaf Kitchen</h1>

<p align="center">A home cooking companion built with <a href="https://github.com/anas1412/loaf">Loaf</a>: recipes, a shopping list, a weekly meal plan and a pantry.</p>

<p align="center"><a href="https://anas1412.github.io/loaf-prototype/">Open Loaf Kitchen</a></p>

## What it shows

Every page is a plain HTML file that starts with one line:

```html
<script src="https://cdn.jsdelivr.net/gh/anas1412/loaf@0.3/loaf.js"></script>
```

| Page | Loaf features |
|---|---|
| `index.html`, Today | live counts, today's meals from the plan, quick add to the shopping list, favorite recipes |
| `recipes.html` | a form with text, numbers, a dropdown, notes and a toggle; cards with click-to-edit, favorites, delete, search and a favorites filter |
| `shopping.html` | tick off, edit and remove items |
| `plan.html` | one list per day of the week, in tabs that open on today |
| `pantry.html` | amounts, units and a "running low" flag |
| `about.html` | how it's built, and a button to delete everything |

The sidebar, top bar and footer are shared through `_layout.html`. The bakery look is a custom daisyUI theme in `_layout.html`, and visitors can switch to any of the 35 built-in themes.

Everything is saved in the visitor's own browser, so each person has their own private kitchen.

## Run it yourself

Open this folder with any local web server, for example `npx serve` or `python3 -m http.server`, then visit the address it prints.
