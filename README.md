# css-only-lightbox
A lightbox written in CSS.  Does require js and does not rely on target attribute.
```
<label for="UNIQUE-CHECKBOX-ID">Click here to open lightbox</label>

<input id="UNIQUE-CHECKBOX-ID" type="checkbox" class="css-lightbox-toggle" />
<div class="css-lightbox"> 
    <label for="UNIQUE-CHECKBOX-ID" class="lightbox-outside lightbox-animation-fade-in" />
    <div  class="lightbox-inside lightbox-animation-fade-in">
            
                <!-- Content -->

    </div>
</div>
```
