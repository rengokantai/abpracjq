## abpracjq
###CHAPTER 5 Events in jQuery
####The Event() Method in jQuery
```
var jQueryEvent = $.Event('click');
list.trigger(jQueryEvent);
```
free from depending on the user interaction.  
using shorthand
```
list.click();
```

The currentTarget denotes the DOM element that is directly tied to the event, 
whereas the relatedTarget denotes the DOM element that has contributed to the event.
[example](http://jsfiddle.net/6rckdyfh/2/)  
currentTarget: not change. Element where event bind to.  
relatedTarget: where triggers

####Events Propagation and Events Bubbling
#####The Event Capturing and Event Bubbling Models
