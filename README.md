# KnockoutOwlCarousel2

This is Knockout binding that allow you easily use Owl.Carousel 2 with observableArray and dynamic generated content. 

## Usage 
```
 <div class="owl-carousel owl-theme" data-bind="owlCarousel: {data: items, options:{margin:10, nav:true }}">
    <div class="item" data-bind="text: $data"></div>    
 </div>
```
Live example on [jsfiddle.net](http://jsfiddle.net/s2reh01L/5/)

**owlCarousel** binding has same parameters like [foreach](http://knockoutjs.com/documentation/foreach-binding.html), 
plus extra parameter called "options". 

"options" is optional parameter which contain settings to initialize owlCarousel  

Enjoy

