# jquery-screamer
jQuery plugin for popup messages

[DEMO](https://maximzhurkin.github.io/jquery-screamer/)

## Getting Started
### 1. Include [jQuery](https://jquery.com/) and Screamer
```html
<script src="jquery.min.js"></script>
<script src="scrolla.jquery.min.js"></script>
```
### 2. Include styles
```html
<head>
  <link rel="stylesheet" href="dist/screamer.jquery.min.css">
  <link rel="stylesheet" href="dist/screamer.theme.min.css">
</head>
```
### 4. Call Screamer
```javascript
$('#alert').click(function(){
	$().screamer({
		message: 'Its default alert'
	});
});
```
## JavaScript Options
```javascript
$('#alert').click(function() {
	$().screamer({
		title: 'Message',
		message: 'Its default alert',
		button: 'Okay',
		overlayClose: true,
		theme: 'screamer-blue'
	});
});
```