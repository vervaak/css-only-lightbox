#What is it
A lightbox written in CSS.  It does not require js nor rely on target attributes.  

#Getting Started

##Step 1.

Include css-lightbox.css in your html. For default fade-in animations also include css-lightbox-animations.css.
```
<link rel="stylesheet" href="./css-lightbox.css" type="text/css">
<link rel="stylesheet" href="./css-lightbox-animations.css" type="text/css">
```

Define style of element with class .lightbox-inside, which will contain your content.
Here is an example:
```
.lightbox-inside{
    padding: 12px;
    margin-top: 5%;
    min-height: 200px;
    width: 720px;
    text-align: left;
    overflow: scroll;

}    
@media screen and (max-width: 500px) {
    .lightbox-inside {
        width: 300px;
    }    
}
```
##Step 2.

Use this HTML as a template. Label's **for-attributes** must match the checkbox' id.
```
<label for="MY-LIGHTBOX">
CLICK ME
</label>

<input id="MY-LIGHTBOX" type="checkbox" class="css-lightbox-toggle" />
<div class="css-lightbox"> 
    <label  for="MY-LIGHTBOX" class="lightbox-outside lightbox-animation-fade-in" ></label>
    <div  class="lightbox-inside lightbox-animation-slide-down">
    
        Content

    </div>
</div>
```
That's it.

