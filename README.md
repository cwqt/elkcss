<p align="center">
<img src="./elk.svg" width=200> 
<h1>elkCSS</h1>
</p>


## How to use elkCSS (CSS)

- Download `elk.min.css` from this repo
- Move it to your project folder
- Include it in the head via (assuming your stylesheet + html file are in the same directory)

```html
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" type="text/css" href="elk.min.css">

some stuff

</head>
<body>

your code here
```

## How to use elkCSS (SCSS)

- Clone this repo
- Import the elk.scss file into your main scss file

Ideally you should use the elkCSS presets for things like padding and margins, for example:

```scss
.box {
  background-color: red;
  @extend .v_hs;
  @extend .m_p;
}
```

If you get stuck, shoot me an e-mail or contact me on the /wg/ discord server, [https://discord.gg/xW8r4nX](https://discord.gg/xW8r4nX).
