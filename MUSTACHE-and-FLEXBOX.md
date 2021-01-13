# MUSTACHE and FLEXBOX

## JavaScript templating
Templating is an efficient way to render client-side view templates using javascript and a JSON data source. 
Template is written in html markup using special template tags, then processed by a template engine at runtime to replace actual values and convert template to an html file which is served to the client. 

**Mustache** is one such template.

It's "logic-less" because there are no statements, clauses, or for loops, only "tags".
*Mustache.js* is the javascript implementation of Mustache. 

    `Mustache.render(“Hello, {{name}}”, { name: “Sherlynn” });
    // returns: Hello, Sherlynn`

Above, {{name}} is a *placeholder*. After compiling, {{name}} is replaced with the 'name' property we passed it. 

## FLEXBOX
Flexbox is here to save us from floats. 

Flexbox is flexible, meaning it can display dynamic or unknown-size content. 

// Note: Flexbox layout is most appropriate to the components of an application, and small-scale layouts, while the Grid layout is intended for larger scale layouts. //

Items will be laid out either on the **main axis** (x) or **cross axis** (y)

### Properties for parent (.container)
- `display: flex` *this enables flex context for all children*
- `flex-direction` *row or column*
- `flex-wrap` *default is that all items try to fit on one line. enable wrapping here.*
- `flex-flow` *shorthand for flex-direction and flex-wrap*
- `justify-content` *defines alignment along main axis*
- `align-items` *defines alignment along cross axis*
- `align-content` *aligns flex containers lines when extra space exists in cross-axis*

### Properties for child (.item)
- `order` default is source order
- `flex-grow` dictates what amount of available space inside the flex container the item should take up. Unitless ratio. 
- `flex-shrink` allows item to shrink if necessary
- `flex-basis` default element size
- `flex` This is the shorthand for flex-grow, flex-shrink and flex-basis combined.
- `align-self` overrides default alignemnt from parent 
