jQuery.clickOutside
===================

jQuery plugin: do something when click outside of an element, like closing a popup/login/panel


Example
-------

You can hide a sliding in login box when clicking outside of that region:

```js
// For example we can slideUp an already shown (slideDown) element like a login or search form
$("#doSomethingWithThisElement").dClickOutside({ ignoreList: $('#doIgnoreThisElement') }, function (){
  $(this).slideUp();
});
```
