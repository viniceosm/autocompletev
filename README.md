# autocompletev
Auto complete customizable

You **not** need of jQuery

[SEE A EXAMPLE HERE](https://viniceosm.github.io/autocompletev/)


## Example

```html
<link rel="stylesheet" href="autocompletev.css">
<script src="autocompletev.js"></script>
<script src="jquery.min.js"></script>

<input id="inputExample" class="datalist-input" type="text" target="#acExample" autocomplete="off">

<div class="datalist" id="acExample">
    <div class="datalist-option">Vini</div>
    <div class="datalist-option">Christopher</div>
    <div class="datalist-option">Maicon</div>
    <div class="datalist-option">Mateus</div>
</div>
```

```javascript
$(document).ready(function () {
	autocompletev.adicionaEventosDataList('#inputExample');
});
```

### Input
The input need `class="datalist-input"`, attribute `target` that referencies the DIV datalist and also `autocomplete="off"`.

### Datalist
The datalist need of a id for the input text can use. For options use `div.datalist-option`

### Method javascript
The method must be called after creating the input text and the datalist.

```javascript
autocompletev.adicionaEventosDataList(idElement);
```