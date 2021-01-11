# Read: 01 - SMACSS and Responsive Web Design

## Responsive Web Design
* Responsive Web Design - websites continually and fluidly change based on different factors, such as viewport width
* Adaptive Web Design - built to a group of preset factors (think fixed viewport sizes)
* Mobile web design - to build a separate website commonly on a new domain solely for mobile users (no longer favored)
* flexible layouts - the practice of building the layout of a website with a flexible grid, capable of dynamically resizing to any width
* Media queries - provide the ability to specify different styles for individual browser and device circumstances. Good in combination with flexible layouts.
  * height and width are most commonly used, but orientation can also be useful for differentiating between mobile and desktop
  * min and max are used to set stop points
* mobile first - using styles targeted at smaller viewports as the default styles for a website, then use media queries to add styles as the viewport grows.
* viewport meta tag - either the height or width values will define the height or width of the viewport respectively. typically content="width=device-width"
* initial-scale of a website should be set to 1 
* Flexible media - media types need to be scalable, changing their size as the size of the viewport changes: use the max-width property with a value of 100%
## All About Floats
* Floated elements remain a part of the flow of the web page
* analgy here is to text wrapping in print media
* There are four valid values for the float property
  * Left, right, none (default), inherit
* Float’s sister property is clear
  * Clear has the same four valid values as float
* Collapsing almost always needs to be dealt with to prevent strange layout and cross-browser problems. 
  * We fix it by clearing the float after the floated elements in the container but before the close of the container.
* Techniques for Clearing Floats
  * The Empty Div Method
  * The Overflow Method
  * The Easy Clearing Method
* problems with floats include pushdown, 3px jog, and ancient IE problems. 
  * nowadays everyone uses grids or flexbox for layout, but floats are still important for small tweaks.
## Scalable and Modular Architecture for CSS
* SMACSS is a way to examine your design process and as a way to fit those rigid frameworks into a flexible thought process
* By categorizing CSS rules, we begin to see patterns and can define better practices around each of these patterns.
  * Base
  * Layout
  * Module
  * State
  * Theme
* Base rules are the defaults
* Layout rules divide the page into sections. Layouts hold one or more modules together.
* Modules are the reusable, modular parts of our design. They are the callouts, the sidebar sections, the product lists and so on.
* State rules are ways to describe how our modules or layouts will look when in a particular state.
* Theme rules are similar to state rules in that they describe how modules or layouts might look
* using these categories we can better organize our css code and approach design in a sysytematic way.
* CSS Reset is a set of Base styles designed to strip out—or reset—the default margin, padding, and other properties
