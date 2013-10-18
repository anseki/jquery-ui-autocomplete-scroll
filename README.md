# Scrollable jQuery UI Autocomplete for long item list

CSS `max-height`, `overflow-y` and `padding-right` can make scrollable list easy. But that is not beautiful.

Load this script file after loading `jquery.ui.autocomplete.js`.

## Example

```js
$('#txt1').autocomplete({
  maxShowItems: 5, // Make list height fit to 5 items when items are over 5.
  source: list1
});
```
