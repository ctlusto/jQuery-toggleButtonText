# jQuery-toggleButtonText

A really simple, *really* lightweight (go ahead, try and weigh it) plugin that gives your buttons a toggling text label.

Works on both `<input type="button">` and `<button>` elements.  Just label your button as you ordinarily would, and then store the alternate text in a `data-alt-text` attribute.  That's it for the markup.

For example:
```html
<button id="myCoolButton" data-alt-text="Hide Cool Thing">Show Cool Thing</button>
```

Then, you can togglify a jQuery collection in one line:
```javascript
$('#myCoolButton').toggleButtonText();
```

Done and done.

Here's a [live example] if you want to see it with your own two eyes.


[live example]: http://jsbin.com/OsUjatU/1/
