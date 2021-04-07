# 3D-CSS-lib

3D-CSS-lib is a simple 3D CSS library that helps you get started with 3D on websites. This makes it possible for developers to make creative 3D websites with less code and save time. The best part - No javascript necessary!! Because this library was made with pure CSS this is much faster and lightweight than WebGL. This makes it possible to run 3D websites on any modern browser, even on older hardware!!

## Including in browser
```html
<link href="https://appukuttan66.github.io/3D-CSS-lib/lib.css" rel="stylesheet" type="text/css">
```

## Creating a simple cuboid

### HTML
```html

<div class="c">
  <div class="s"></div>
  <div class="s"></div>
  <div class="s"></div>
  <div class="s"></div>
  <div class="s"></div>
  <div class="s"></div>
</div>

```
### CSS

```css

.c {
  transform: rotateX(20deg) rotateY(30deg);
}

```
## Changing the height, width and depth
```css
.c {
  --height: /* the height you want */;
  --width: /* the width you want */;
  --depth: /* the depth you want */;
}
```
## Changing the color
```css
.c {
  --bg: /* color */;
}
```
## Using an image instead of color
```css
.c {
  --bg: url(/* URL to image*/);
}
```
## Tutorials
you can find them at https://appukuttan66.github.io

***Share your awesome creations with me on github discussions.***
