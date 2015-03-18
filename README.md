# KC FAB

KC FAB is a jQuery plugin to create materilize floating action button easily.

### Version
1.0

### How to use

First of all, you need to have a DOM element to hold action buttons:
e.g
```html
<div class="kc_fab_wrapper" ></div>
```
Then in your script, calling the kc_fab on your DOM element.
You can pass in an object array as option to tell the plugin the buttons style and the anchors' link.
```js
var links = [
                {   /* The first object will be the main button */
                    "bgcolor":"red",
                    "icon":"+"
                },
                /* Following are the hidden button list */
                {
                    "url":"http://www.example.com",
                    "bgcolor":"red",
                    "color":"#fffff",
                    "icon":"<i class='fa fa-phone'></i>",
                    "target":"_blank"
                },
                {
                    "url":"http://www.example.com",
                    "bgcolor":"black",
                    "color":"white",
                    "icon":"<i class='fa fa-music'></i>"
                }
            ]
$('.kc_fab_wrapper').kc_fab(links);
```



License
----

MIT

