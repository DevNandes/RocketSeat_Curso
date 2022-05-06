# Selectors

Conecta um elemento HTML com o CSS

## Tipos

* Global selector `*`
* Element/Type selector `h1, h2, p, div`
* ID selector `#box, #container`
* Class selector `.red, .m-4`
* Atribute selector, Pseudo-class, Pseudo-element, e outros

```html
HTML
<div id="container" class="m-40">
	<h1>Título</h1>
	<h2>Subtitulo</h2>
</div>
```

```css
CSS
/* ID selector */
#container {
	width: 200px;
}

/* Class selector */
.m-40 {
	margin: 40px;
}

/* Element/Type selector + Agrupamento de seletores */
h1, h2 {
	color: blue;
	font-size: 60px;
	background: gray;
}

```