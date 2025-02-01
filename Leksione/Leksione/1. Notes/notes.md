# Sisteme Multimediale

Temat e ndryshme qe duhen mesuar ose perseritur

## HTML

### HTML Structure tags

- `<html>`
- `<head>`
- `<body>`

#### `<head>` tags

- `<title>`
- `<base/>`
- `<link/>`
- `<style>`
- `<script>`
- `<meta/>`

### Basic Html Elements

- `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`
- `<p>`
- `<a>`
  - `[target]`
  - `[href="mailto:help@help.com?subject=Hello"]`
- `<img/>`
- `<picture>`
  - `<source/>`
    - `[media="(min-width: 650px)]`
    - `[srcset="img_lule_pink.jpg]"`
- `<div>`
- `<span>`
- `<iframe>`

### Listat

- `<ol>`
- `<ul>`
  - `<li>`

### Tabelat

- `<table>`
- `<tr>`
- `<td>`
- `<th>`

#### Table tags for the structure

- `<thead>`
- `<tbody>`
- `<tfoot>`

#### Table tags for the styling of the table

- `<colgroup>`
- `<col/>`

#### Table attributes

- `[row-spam]`
- `[col-spam]`
- `[border]`

### Video & Audio

- `<video>`
- `<audio>`
  - `<source/>`

### Format

- `<form action="" >`
- `<label for="">`
- `<textarea row="" col="">`
- `<fieldset>`
  - `<legend>`

#### Form Input fields

---

**NOTE**

You can add an `[id]` attribute to each `<input>` element and use that `id` as the value for the `[for]` attribute in the `<label>` tag

---

- `<input type="text" />`
- `<input type="number" min="" max="" />`
- `<input type="password" />`
- `<input type="email" />`
- `<input type="tel" />`
- `<input type="search" />`
- `<input type="url" />`
- `<input type="date" />`
- `<input type="month" />`
- `<input type="week" />`
- `<input type="time" />`
- `<input type="color" />`
- `<input type="radio" name="" value="" />`
- `<input type="checkbox" name="" value="" />`
- `<input type="range" min="" max="" />`
- `<input type="file" multifile />`
- `<select name="">`

  - `<optgroup label="">`
  - `<value="">`
    - `[selected]`

- `<input type="button" value="" />`
- `<input type="reset" value="" />`
- `<input type="submit" value="" />`

---

- `<input list="" />`
  - `<datalist id="">`
    - `<option>`

### HTML Semantic Elements

- `<aside>`
- `<article>`
- `<address>`
- `<time>`
- `<details>`
- `<header>`
- `<nav>`
- `<main>`
- `<section>`
- `<summary>`
- `<footer>`
- `<figure>`
  - `<figurecaption>`

### Stupid HTML tags (if you want to kill yourself)

- `<map>`
  - `<area/>`

## CSS

### CSS Propreties

- `margin`
- `padding`
- `width`
- `max-width`
- `height`
- `max-height`
- `color`
- `background-color`
- `border`
- `border-style`
- `border-radius`
- `border-image`
- `box-shadow`
- `font-size`
- `font-weight`
- `font-family`
- `font-variant`
- `text-aligment`
- `text-decoration`
- `list-style-type`
- `border-spacing`
- `border-collapse`
- `background-image`
- `background-repeat`
- `background-position`
- `background-attachment`
- `box-sizing: border-box;`

### CSS FlexBox

Please search `flexbox` in Google. Teacher's lectures were horrible 😭 and I don't wnat to make the same mistake by tring to explain `flexbox` here.

If you want to learn more about `flex` click [here](https://www.youtube.com/watch?v=wsTv9y931o8&t=23s).

### CSS Selectors

- `tag` selector

Perzgjedh te githe elementet `h1`

```css
h1 {
  color: red;
}
```

- `attribute` selector

Perzgjedh te githe elementet me atribution `href`

```css
[href] {
  color: red;
}
```

- `id` selector

Perzgjedh elementin me id `title`

```css
#title {
  color: red;
}
```

- `class` selector

Perzgjedh te githe elementet me klasen `button`

```css
.button {
  color: red;
}
```

- `tag + id/class` selector

```css
/* Perzgjedh ate `div` me id `r` */
div#r {
  bacground-color: red;
}

/* Perzgjedh ato `p` me class`b` */
p.b {
  bacground-color: blue;
}
```

- `descendant` selector

Perzgjedh te githe elementet `h2` brenda elementeve
me class `container`

```css
.container h2 {
  color: red;
}
```

- `child combinator` selector

Perzgjedh te githe elementet `h2` brenda elementeve
me class `container`, qe jan efemije direkte te tij

```css
.container > h2 {
  color: red;
}
```

- `adjacent sibling` selector

Perzgjedh te githe elementet `p` qe jane poshte
nje elementi `div` ne dokumentin HTML

```css
div + p {
  color: red;
}
```

- `general sibling` selector

Perzgjedh cdo element `p` qe eshte pas nje elementi `div`, por jo domosdoshmerisht fiks pas tij

```css
div ~ p {
  color: red;
}
```

### CSS Pseudo-Elements

- `::before` Vendos `content` para elementit
- `::after` Vendos `content` pas elementit
- `::selection`/ `::-moz-selection` Perzgjedh highlight-in kur bejme select

### CSS Pseudo-classes

- `:link` Ndryshon ngjyren e linkut
- `:visited` Ndryshon ngjyren e link pasi e kemi vizituar
- `:hover` Kur kemi mouse-in siper elementit
- `:active` Kur jemi duke klikuar mbi elementin
- `:first-letter ` Perzgjedh shkronjen e pare
- `:first-line` Perzgjedh rreshtin e pare
- `:first-child ` Perzgjedh femijen e pare te cilit do element
- `:checked` Perzgjedh ato `radio buttons` ose `checkboxes` qe jane te selektuar
- `:lang(sq)` Perzgjedh ato element qe kane atributin `lang="sq"`

## JavaScript

### JavaScript Popup Boxes

- `Alert` Box

```js
window.alter('Hellot there')
```

- `Confirm` Box

```js
if (confirm('Press a button!')) {
  txt = 'You pressed OK!'
} else {
  txt = 'You pressed Cancel!'
}
```

- `Prompt` Box

```js
let person = prompt('Please enter your name', 'Harry Potter')
let text
if (person == null || person == '') {
  text = 'User cancelled the prompt.'
} else {
  text = 'Hello ' + person + '! How are you today?'
}
```
