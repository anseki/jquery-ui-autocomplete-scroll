# jquery-ui-autocomplete-scroll

Scrollable jQuery UI Autocomplete for long item list.  
CSS `max-height`, `overflow-y` and `padding-right` can make scrollable list easy. But that is not beautiful.

[Demo](http://jsfiddle.net/7PzVz/)

## Usage

Load the `jquery.ui.autocomplete.scroll.js` script file after loading `jquery.ui.autocomplete.js` etc.

```html
<link rel="stylesheet" type="text/css" href="//ajax.googleapis.com/ajax/libs/jqueryui/1.10.3/themes/blitzer/jquery-ui.css" />
<script type="text/javascript" src="//ajax.googleapis.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>
<script type="text/javascript" src="//ajax.googleapis.com/ajax/libs/jqueryui/1.10.3/jquery-ui.min.js"></script><!-- jquery.ui.autocomplete.js is included -->
<script type="text/javascript" src="/path/to/jquery.ui.autocomplete.scroll.js"></script>
```

The `maxShowItems` is added to Autocomplete options. It accept the number of items which is max height of item list.

## Example

```js
$('#txt1').autocomplete({
  maxShowItems: 5, // Make list height fit to 5 items when items are over 5.
  source: list1
});
```
