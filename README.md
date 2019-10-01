# Custom Checkbox and Radio buttons CSS / SCSS

CSS and SCSS only solution for custom checkboxes and radios buttons.

### **[View the Demo](https://joaoproenca.github.io/custom-checkbox-radio-css-and-scss/)**

![Custom checkboxes and radios buttons](https://joaoproenca.github.io/custom-checkbox-radio-css-and-scss/example/custom-checkbox-radio.gif)


## Include HTML

### Depending on your type of selection form (**checkboxes** or **radio buttons**) use:


```html
<label class="selection selection__check selection__large">
  <input type="checkbox" disabled checked>
  <span class="selection--mark"></span>
  <span class="selection--caption">Checkbox</span>
</label>
```

```html
<label class="selection selection__radio selection__large">
  <input type="radio" name="radio-1" checked>
  <span class="selection--mark"></span>
  <span class="selection--caption">Radio button</span>
</label>
```

#### Rules:
* All the HTML tags and CSS class must be used in this way
* You can alternatively change the sub-modules types (**selection__check** or **selection__radio**)
* You can alternatively change the sub-modules sizes (**selection__large**, **selection__medium** or **selection__small**)


## Include CSS

### Use the **CSS** file or the **SCSS** file (if you have a preprocessor):  
* SMACSS (Scalable and Modular Architecture for CSS) usage:  
  * Parent module (selection)  
  * Children modules (mark and caption)    
  * Sub-modules according to the type (checkbox and radio button) and sizes (large, medium and small)  
* Single-line CSS coding
* Variables (SCSS only)
* Mixins (SCSS only)
* Reset code (not necessary if it's already present in your the code)
* Global code (specific to style the example page)


## Customise

Written in a non-invasive kinda way, so you can add your own styles. You can change the colours, sizes and the check mark style ```.selection--mark::before```. In the SCSS file you can simply override the various variables for colours and sizes.

## Browser Support

IE10 +
