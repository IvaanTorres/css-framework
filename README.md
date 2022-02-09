# CSS Framework

I made this CSS Framework with the objective of learning how SASS & BEM work together.

I'm updating this repo constantly, adding new features everytime.

## Technologies

- ![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
- **BEM** Methodology with prefixes + **ITCSS** structure (**BEMIT**)

## Starting up

- Prefixes
  - Block/Component (**c-**)
  - Layout (**l-**)
  - Global utility (**g--**)
- Responsive breakpoints (**@**)
  - mobile
  - tablet
  - desktop
- API to get the array values and make easier the creation of classes

## Examples

```html
<button class="c-button c-button--big g--margin-top-xl">hey</button>
```

```html
<nav class="c-navbar">
  <ul class="c-navbar__items">
    <li class="c-navbar__item">Home</li>
    <li class="c-navbar__item c-navbar__item--alternative">About</li>
  </ul>
</nav>
```

```html
<div class="l-col l-col--1 tablet@l-col--2 desktop@l-col--3 g--gap-sm">
  <div class="c-card l-hamburger">
    <h2 class="c-card__title">Title</h2>
    <p class="c-card__description">Description</p>
    <button class="c-card__button">Button</button>
  </div>
  <div class="c-card l-hamburger">
    <h2 class="c-card__title">Title</h2>
    <p class="c-card__description">Description</p>
    <button class="c-card__button">Button</button>
  </div>
  <div class="c-card l-hamburger">
    <h2 class="c-card__title">Title</h2>
    <p class="c-card__description">Description</p>
    <button class="c-card__button">Button</button>
  </div>
</div>
```

## Personalize the framework

- Create new components, layouts or global utilities according to your own project. 
- Modify the variables or add new ones.
- Change the brakpoint values in seconds, modify the separator or even, add new breakpoints.

## Author

Linkedin: [http://linkedin.com/in/ivan-torres-garcia](http://linkedin.com/in/ivan-torres-garcia)
