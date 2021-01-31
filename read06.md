# color 
The color property allows you to specify the color of text inside an element. 
You can specify any color in CSS in one of three ways:
1. RGB values :
These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90).
2. HEX codes:
These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80 .
3. There are 147 predefined color names that are recognized by browsers. For example: DarkCyan
**notice** 
* Anything between the `/*` symbols and the `*/` symbols will not be interpreted by the browser. that allows you to add comments to your CSS files.
* CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.
# Understanding Color
- Every color on a computer screen is created by mixing amounts of red,
green, and blue. To find the color you want, you can use a color picker.
- Color picking tools are available in image editing programs like Photoshop and GIMP. You can see the RGB values specified next to the radio buttons that
say R, G, B.
- The hex value is provided next to the pound or hash # symbol. There is also a
good color picking tool at: colorschemedesigner.com
* anther way to pick color is HSB
- Hue
Hue is near to the colloquial idea of color. Technically speaking however, a color can also have saturation and brightness as well as hue.
- Saturation
Saturation refers to the amount of gray in a color. At maximum saturation, there would be no gray in the color. At minimum saturation, the color would be mostly gray.
- Brigh tness
Brightness (or "value") refers to how much black is in a color. At maximum brightness, there would be no black in the color.At minimum brightness, the color would be very dark.
* Contrast:
When picking foreground and background colors, it is important to ensure that there isenough contrast for the text to be legible.
- Low Contrast:Text is harder to read when there is low contrast between background and foreground colors.
- High Contrast :Text is easier to read when there is higher contrast between background and foreground colors.
- Medium Contrast:For long spans of text, reducing the contrast a little bit improves readability.
## CSS 3: Opacity (opacity, rgba):
CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements.The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).
## CSS 3: HSL Colors :
CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation, and lightness values.
- hue: 
Hue is the colloquial idea of color. In HSL colors, hue is often represented as a color circle where the angle represents the color, although it may also be shown as a slider with values from 0 to 360.
- saturation:
Saturation is the amount of gray in a color. Saturation is represented as a percentage. 100% is full saturation and 0% is a shade of gray.
- lightness :
Lightness is the amount of white (lightness) or black (darkness) in a color. Lightness is represented as a percentage. 0% lightness is black, 100% lightness is white, and 50% lightness is normal. Lightness is sometimes referred to as luminosity.
**notice** that lightness is a different concept to brightness.Graphic design software (such as Photoshop and GIMP) have color pickers that use hue, saturation, and brightness — but brightness only adds black, whereas lightness offers both white and black.
## CSS 3: HSL & HSLA :
The value of the property starts with the letters hsl, followed by individual values inside parentheses for:
- HUE: 
This is expressed as an angle (between 0 and 360 degrees).
- saturation :
This is expressed as a percentage .
- lightness :
This is expressed as a percentage with 0% being white, 50% being normal, and 100% being black
- alpha :
This is expressed as a number between 0 and 1.0. For example, 0.5 represents 50% transparency, and 0.75 represents 75% transparency.
