<p align="center">
<img src="./src/assets/elk.svg" width=200> 
</p>

# elkCSS

## How to use elkCSS (CSS)

- Download `elk.min.css` from this repo
- Move it to your project folder
- Include it in the `head`

```html
<link rel="stylesheet" type="text/css" href="elk.min.css">
```

## How to use elkCSS (SCSS)

- Clone this repo
- Import the `elk.scss` from `./src/sass/elk.scss` file into your main scss file

Ideally you should use the elkCSS presets for things like padding and margins, for example:

```scss
.box {
  background-color: red;
  @extend .v_hs;
  @extend .m_p;
}
```