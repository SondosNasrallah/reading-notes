# Summerization

### Introduction to CSS
- CSS treats each HTML element as if it appears inside
its own box and uses rules to indicate how that
element should look.
- Rules are made up of selectors (that specify the
elements the rule applies to) and declarations (that
indicate what these elements should look like).
- Different types of selectors allow you to target your
rules at different elements.
- Declarations are made up of two parts: the properties
of the element that you want to change, and the values
of those properties. For example, the font-family
property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.
- CSS rules usually appear in a separate document,
although they may appear within an HTML page.




### Color 
- Color not only brings your site to life, but also helps
convey the mood and evokes reactions.
- There are three ways to specify colors in CSS:
  - RGB values : These express colors in terms of how much red, green   and blue are used to make it up. For example: rgb(100,100,90)
  - Hex codes : These are six-digit codes that represent the amount     of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80
  - Color names : There are 147 predefined color names that are recognized by browsers. For example: DarkCyan



  - Background Color : By default, most browser windows have a white      background, but browser users can set a background color for
     their windows, so if you want to be sure that the background is white you can use the background-color property on the <body> element.



  - Contrast : When picking foreground and background colors, it is      important to ensure that there is enough contrast for the text      to be legible. 
     - Low
     - High
     - Medium

  - CSS3 has introduced an extra value for RGB colors to indicate          opacity. It is known as RGBA.


  - Opacity (CSS3 RGBA): 
     The CSS3 rgba property allows you to specify a color, just like
      you would with an RGB value, but adds a fourth value to
      indicate opacity. This value is known as an alpha value and is
      a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity
      and 0.15 is 15% opacity). The rgba value will only affect the
      element on which it is applied (not child elements).


  - CSS3 also allows you to specify colors as HSL values, with an         optional opacity value. It is known as HSLA.


  - CSS3 HSL Colors introduces an entirely new and intuitive way to specify colors using hue, saturation, and lightness values.


  - It is important to ensure that there is enough contrast between     any text and the background color (otherwise people will not be     able to read your content).