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