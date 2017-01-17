# Simple-Item-Vertical-Slider
Simple Item Vertical Slider for slide menu item or other element (e.g. like news item, image and other) vertically.

#EXAMPLE STRUCTURE
##HTML
```html
<div class="articleList">
    <div class="items">
        <div class="item">
            <a href="#">
                <img src="img/dummy.png">
                <div class="desc">
                    <h4>dummy</h4>
                </div>
            </a>
        </div>
    </div>
    <div class="control">
        <div class="down"></div>
        <div class="up"></div>
    </div>
</div>
```
##JS
```javascript
For init plugin need manually change item variables:
var list = $('.articleList'); /* -- block container */
var list_items = list.find('.items'); /* -- items container */
var list_item = list_items.find('.item'); /* -- item destination */

var control = list.find('.control'); /* -- controls container */
var up = control.find('.up'); /* -- up button */
var down = control.find('.down'); /* -- down button */
```

All of this variables may be change

###AS IS
