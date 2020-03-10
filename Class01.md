# Responsive Web Design
  * Websites suitable for all users born from the advent of cell phones
  * Should work on every device adn every screen size
  * Should be intuitive and gratifying
  * Responsive vs Adaptive vs Mobile
    * Mobile requires its own website on its own domain (usually)
  * Flexible layouts
    * Build website with a flexible grid capable of resizing to any width
    * Do not used fixed measurement units
  * Media queries
    * Extension of media types
    * Allow to specify different styles for different viewports
    * `@media`
    * Logical operators can be used in media queries
      * and, not, only
  * Mobile First
    * Create a mobile friendly styling and scale up 
  * Flexible Media
    * Media needs to be scalable with the viewport
# Floats
* Float is a positioning property
* Text flows around floats
* Floated elements remain a part of the flow of the webpage. Contrary to absolute positioning
* Clear is float's sister property
  * Moves itself down past the float
* Problems
  * Pushdown
  * Double Margin Bug
    * IE6 doubles the margins with floats
  * 3px jog
    * Text next to floats is kicked 3px 
# Grids
* Most websites use a grid implicitly or explicitly
* A box level element is as wide as its parent container
* Gutters are the most difficult part of grids
* `box-sizing: border-box` helps solve some of the complexity of gutters along with fixed sizes for gutters
# CSS Float Escalator
* Floats create alternate flows
* CSS should account for normal, left, and right
* Respect the passing lane
* Space is filled in around floated elements
* Use clear to keep a space empty
# Scalable and Modular Architecture for CSS
* Base
  * Element selector, descendent selector, child selector, and pseudo classes
* Module
  * Avoid using ids
  * Meat of page
  * Modules sit inside layout components
* Layout
  * Header, footer, nav
* State 
  * Overrides other sytles
* Theme
  * Give site look and feel (holiday)