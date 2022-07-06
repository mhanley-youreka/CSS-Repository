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
    
## Adjust Youreka Form Colors

### Save Buttons Bar

```css
.slds .buttons-fixed {
    background-color: #009ACD;
}
```


### Form Template Name

```css
h1.formName,
h3.slds-text-heading--small {
   color: #A95014; 
}
```


### Form Background Color

```css
body#complete-form.slds {
    background-color: #94E9E8;
}
```


### Section Header Font Color

```css
.slds .currentPageContainer { 
    color: #ecf2fb;  
}
```


### Section Header and Footer Background Color & Border Color

```css
.slds .slds-card { /* ELEMENTS: Section Header and Footer */
    background-color: #418638;
    border-color: #94E9E8;
}
```


### Section Body Background, Border, and Text Color

```css
.slds .slds-card__body.OR-card__body.slds-p-left--small { 
    background-color: #75A05F;
    border-color: #94E9E8;
    color: #fff;  
}
```

### Attachments Count Badge, Attachments, Multi-select Picklist Options Text & Background Color

```css
.slds .controls .selected-files .file-preview, /* ELEMENT: Attachment Count Badge */
.slds .controls .slds-file-selector .slds-badge.slds-theme--info, /* ELEMENT: Attachments */
.ms-selectable .ui-widget-content.ui-selectee.ui-selected { /* ELEMENT: Selected Multi-select Picklist Options */
    color: #75A05F;  /* STYLE: Text color */
    background-color: #fff;
}
```

### Checkbox and Radio Button Label Colors

```css
.slds .slds-form-element__control .slds-form-element__label,
.slds .slds-card__body.OR-card__body.slds-p-left--small  .control-label { 
    color: #fff !important;  
} 
```


    
