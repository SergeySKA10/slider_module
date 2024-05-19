# slider_module
Slider module for website

This module is intended to implement a slider on a website page.
The module is implemented in a native Java script, using the ES6 standard. Slider in the form of a carousel.

Usage:

1. Set up your HTML markup:
```
<div class="your class slider">
    <div class="your class arrows">
        <div class="prev"></div>
        <span class="your class current"></span>
        <span class="your class total"></span>
        <div class="next"></div>
    </div>
    <div class="your class wrapper">
        <div class="your class field">
            <div class="your class slide"></div>
            <div class="your class slide"></div>
            <div class="your class slide"></div>
        </div>
    </div>
</div>
```
2. Сopy the code from the slider.js file to your separate slider file
   
3. Import using command 'import slider from ...' in your main file 'main.js'
   
4. In the main file call the function slider({}) inside which, as a parameter, pass an object
   with the following properties:
```
slider({
  sliderSelector: 'your selector slide',
  slide: 'your selector slider',
  wrapper: 'your selector wrapper',
  totalCounter: 'your selector total',
  arrows: 'your selector arrows',
  field: 'your selector field',
  currentCounter: 'your selector current',
  color: 'color for dots'
})
```    
