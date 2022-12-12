# RGB

###### 255 on each of the rgb created the color white
###### 127 on the G "green" creates normal green
 

  # Tertiary colors 
  
  ##### are created by combining a primary with a nearby secondary color.

  # Color Wheel

  ##### A color wheel is a circle where similar colors, or hues, are near each other, and different ones are further apart. For example, pure red is between the hues rose and orange.

##### Two colors that are opposite from each other on the color wheel are called complementary colors. If two complementary colors are combined, they produce gray. But when they are placed side-by-side, these colors produce strong visual contrast and appear brighter.

# Hex values


##### A very common way to apply color to an element with CSS is with hexadecimal or hex values. While hex values sound complicated, they're really just another form of RGB values.

##### Hex color values start with a # character and take six characters from 0-9 and A-F. The first pair of characters represent red, the second pair represent green, and the third pair represent blue. For example, #4B5320.

##### With hex colors, 00 is 0% of that color, and FF is 100%. So #00FF00 translates to 0% red, 100% green, and 0% blue, and is the same as rgb(0, 255, 0).

# HSL

##### The CSS hsl function accepts 3 values: a number from 0 to 360 for hue, a percentage from 0 to 100 for saturation, and a percentage from 0 to 100 for lightness.

##### If you imagine a color wheel, the hue red is at 0 degrees, green is at 120 degrees, and blue is at 240 degrees.

##### Saturation is the intensity of a color from 0%, or gray, to 100% for pure color.

# Linear Gradient

##### A gradient is when one color transitions into another. The CSS linear-gradient function lets you control the direction of the transition along a line, and which colors are used.

##### gradientDirection is the direction of the line used for the transition. color1 and color2 are color arguments, which are the colors that will be used in the transition itself. These can be any type of color, including color keywords, hex, rgb, or hsl. also if n gradient direction is set 180 will be set automatically

## border left

##### The border-left shorthand property lets you to set the left border's width, style, and color at the same time. border-left: width style color;


## vh
##### The vh unit stands for viewport height, and is relative to 1% of the height of the viewport.

## fieldset tag
##### tag is used to group related elements in a form.
##### The <fieldset> tag draws a box around the related elements.

## rem
##### The rem unit stands for root em, and is relative to the font size of the html element.

# required
##### to make an input required add required attribute to the input

## custom validation
##### Add custom validation to the password input element, by adding a minlength attribute with a value of 8. Doing so prevents inputs of less than 8 characters being submitted.

## pattern attribute

#### With type="password" you can use the pattern attribute to define a regular expression that the password must match to be considered valid. [a-z0-5]{8,} regex that means
##### lower case letters a-z numbers 0 - 5 min length of 8

## Radio Button trick
##### if you give radio buttons the same name attribute tiu cant click both at the same time

## Las of type pseudo class
##### The :last-of-type CSS pseudo-class represents the last element of its type among a group of sibling elements.

## Unset

##### The unset CSS keyword resets a property to its inherited value if the property naturally inherits from its parent, and to its initial value

# The box model
##### An element’s content has two dimensions: a height and a width. By default, the dimensions of an HTML box are set to hold the raw contents of the box.The CSS height and width properties can be used to modify these default dimensions.

### Margin
##### In CSS, the margin: 0 auto property is used to horizontally center an element within its container. This property sets the element's top and bottom margins to 0, and left and right margins to auto, which causes the element to be horizontally centered within its container. The margin property also lets you center content. However, you must follow a few syntax requirements. n order to center an element, a width must be set for that element. Otherwise, the width of the div will be automatically set to the full width of its containing element

### border
##### width—The thickness of the border. A border’s thickness can be set in pixels or with one of the following keywords: thin, medium, or thick.style—The design of the border. Web browsers can render any of 10 different styles. Some of these styles include: none, dotted, and solid.color—The color of the border. Web browsers can render colors using a few different formats, including 140 built-in color keywords.

### padding
##### The padding property is often used to expand the background color and make the content look less cramped.

### margin
##### Margin refers to the space directly outside of the box. The margin property is used to specify the size of this space.

### overflow
##### The overflow property controls what happens to content that spills, or overflows, outside its box. hidden—when set to this value, any content that overflows will be hidden from view.croll—when set to this value, a scrollbar will be added to the element’s box so that the rest of the content can be viewed by scrolling.visible—when set to this value, the overflow content will be displayed outside of the containing element. Note, this is the default value.
