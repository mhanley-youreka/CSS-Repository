# Youreka CSS Snippets  
      
## Set Universal Font Size

```css
.slds {
	font-size: 24px !important; 
}
```    

## Set Relative Font Size

### Template Name

```css
.slds #formContent h1.formName {
	font-size: 2.285em;
}
``` 

### Form Name

```css
.slds #formContent h3.slds-text-heading--small {
	font-size: 1.286em;
}
```

### Attachment Upload Button Font Size

```css
.slds span.slds-button {
	line-height: 2.43em;
}
```

### Section Header Font Size

```css
.form-section.slds-card h2 {
	font-size: 1.28em;
}
```

### Checkbox/Radio Button Option Label Text Size

```css
.slds .slds-form-element__control .slds-radio .slds-form-element__label,
.slds .slds-form-element__control .slds-checkbox .slds-form-element__label {
	font-size: 1em;
}
```



## Adjust Button and Icon Sizes

### Save Buttons Size

```css
.slds .buttons-fixed button {
	line-height: 2.5em;
} 
```     


### Go To Page Select Icon Size 

```css
.slds .buttons-fixed .slds-select.goToPage,
.slds .buttons-fixed .pagination-container .slds-select_container,
.slds .buttons-fixed .pagination-container .slds-select_container select {
	width: 7.15em;
	height: 2.44em;
}
```     

### Select Arrows Size 

```css
.slds #mainForm .slds-select_container:before,
.slds #mainForm .slds-select_container:after {
  border-left-width: 0.214em;
  border-right-width: 0.214em;
}
.slds #mainForm .slds-select_container:before {
  border-bottom-width: 0.357em;
  top: calc((2.429em / 2) - 0.429em);
}
.slds #mainForm .slds-select_container:after {
  	border-top-width: 0.357em;
  	bottom: calc((2.429em / 2) - 0.429em);
}
```  

### Button Icon Size

```css
.slds svg.slds-button__icon {
	height: 1.143em;
	width: 1.143em;
}
```  

### Attachment Upload Button

```css
.slds button.slds-button {
	line-height: 2.385em;
}
```

### Checkbox/Radio Button Size

```css
.slds .slds-form-element__control .slds-radio .slds-radio--faux,
.slds .slds-form-element__control .slds-checkbox .slds-checkbox--faux {
	width: 1em;
	height: 1em;
}
```

### Checkbox & Radio Button check size

```css
.slds .slds-form-element__control .slds-radio [type="radio"]:checked + .slds-radio--faux::after, 
.slds .slds-form-element__control .slds-radio [type="radio"]:checked ~ .slds-radio--faux::after
.slds .slds-form-element__control .slds-checkbox [type="checkbox"]:checked + .slds-checkbox--faux::after, 
.slds .slds-form-element__control .slds-checkbox [type="checkbox"]:checked ~ .slds-checkbox--faux::after {
	border-bottom-width: 0.143em;
  	border-left-width: 0.143em;
	height: 0.286em;
  	width: 0.59em;
}
```

### Date Input Selector Icon

```css
.slds .slds-form-element .input-glyphicon-calendar {
  	padding-top: 0.5em;
}
```
    

    
