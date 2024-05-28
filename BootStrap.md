# BootStrap

## Getting Started

## section
- [Fluid container](#Fluidcontainer)




---
## Fluid container 

In the HTML5 and CSS section of freeCodeCamp we built a Cat Photo App. Now let's go back to it. This time, we'll style it using the popular Bootstrap responsive CSS framework.

Bootstrap will figure out how wide your screen is and respond by resizing your HTML elements - hence the name responsive design.

With responsive design, there is no need to design a mobile version of your website. It will look good on devices with screens of any width.

You can add Bootstrap to any app by adding the following code to the top of your HTML:

<br>

```html
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous"/>`
```

## Responsive image mobile

to make the image mobile responsive , we all need to add the `image-responsive` class to our image tag, so by doing this the image should perfectly fit the width of our page.

```html
<img  class="image-style-exemple image-reponsive" alt="image-fontcvzsfweerdsa">
```

## Center text with bootstrap

To center an element in a page to look better we all need to do id to add class `text-center` to our element.

```html
<h2 class="red-text text-center">your text</h2>
```
## create bootstrap buttom

The `.btn` classes are designed to be used with the `<button>` element. However, you can also use these classes on `<a>` or `<input>` elements

```html
<a class="btn btn-primary" href="#" role="button">Link</a>
<button class="btn btn-primary" type="submit">Button</button>
<input class="btn btn-primary" type="button" value="Input">
```
> **NB** `.btn-primary` it the main colors to use and useful for highlinghing actoins. 

> **NB** `.btn-info` is used to call attention to optional actions that the user can take. 

> **NB** `.btn-outline-*` it remove all background images and colors on any button.
```html
<button type="button" class="btn btn-outline-primary">Primary</button>
<button type="button" class="btn btn-outline-secondary">Secondary</button>
<button type="button" class="btn btn-outline-success">Success</button>
<button type="button" class="btn btn-outline-danger">Danger</button>
<button type="button" class="btn btn-outline-warning">Warning</button>
<button type="button" class="btn btn-outline-info">Info</button>
<button type="button" class="btn btn-outline-light">Light</button>
<button type="button" class="btn btn-outline-dark">Dark</button>
```
> **NB** For fancy larger or smaller buttons? Add `.btn-lg` or `.btn-sm` for additional sizes

## Add Font Awesome Icons
Font Awesome is a convenient library of icons. These icons can be webfonts or vector graphics. These icons are treated just like fonts. You can specify their size using pixels, and they will assume the font size of their parent HTML elements.

add this following code to any app:
```html
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">
```