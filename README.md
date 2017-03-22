# Popup

Popup is a popup window with any HTML content that pops up over App's main content. Popup as all other overlays is part of so called "Temporary Views".

Popup Layout
Popup layout is pretty simple. All you need to do is to put <div class="popup"> Any popup content here </div> right in the body:

```
<body>
  ...
  <div class="popup">
    Any HTML content goes here
  </div>
</body>            
```

Popup Size
By default Popup has a bit different size on phones and tablets (iPad). On phones it is fullscreen while on tablets it is 630px width and height. If you want to make it fullscreen size on tablets, you should add additional "tablet-fullscreen" class to the required popup:

``` 
<body>
  ...
  <!-- This popup has fullscreen size on tablets -->
  <div class="popup tablet-fullscreen">
    Any HTML content goes here
  </div>
</body> 
  ```