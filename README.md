# adapt-rssfeed 

**rssfeed** is a *presentation component* 


**rssfeed**'s simple purpose is to present text with a library to include an RSS feed. The text may include HTML.


## Settings Overview

The attributes listed below are used in *components.json* to configure **rssfeed**, and are properly formatted as JSON in [*example.json*](https://github.com/adaptlearning/adapt-contrib-text/blob/master/example.json). 


### Attributes

[**core model attributes**](https://github.com/adaptlearning/adapt_framework/wiki/Core-model-attributes): These are inherited by every Adapt component. [Read more](https://github.com/adaptlearning/adapt_framework/wiki/Core-model-attributes).

**_component** (string): This value must be: `rssfeed`.

**_classes** (string): CSS class name to be applied to **rssfeed**’s containing `div`. The class must be predefined in one of the Less files. Separate multiple classes with a space.

**_layout** (string): This defines the horizontal position of the component in the block. Acceptable values are `full`, `left` or `right`.  

**title** (string): A reference title for the component. **title** is distinct from the **displayTitle** which, if present, appears above the component. **title** provides the opportunity to use a shortened form in tighter spaces, such as in menus or in the drawer.  

**displayTitle** (string): Optional text that will display as a title or header above the component. It can be used as a headline.   

**instruction** (string): This optional text appears above the component. It is frequently used to
guide the learner’s interaction with the component.

**body** (string): Although optional, this text constitutes what is thought of as the primary *text* of the **rssfeed** component. HTML is permitted.  
<div float align=right><a href="#top">Back to Top</a></div>

## Limitations

No known limitations.   


----------------------------
**Version number:**  0.1.1   
**Framework versions:** 2.0  
**Accessibility support:** WAI AA   
**RTL support:** yes  
**Cross-platform coverage:** Chrome, Chrome for Android, Firefox (ESR + latest version), Edge 12, IE 11, IE10, IE9, IE8, IE Mobile 11, Safari for iPhone (iOS 8+9), Safari for iPad (iOS 8+9), Safari 8, Opera    
