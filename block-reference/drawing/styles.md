# Drawing > Styles

***

## Color and Font

### Create Color (from RGB)

![rgb-block](http://static.stencyl.com/pedia2/block-images/9%20-%20Drawing/1%20-%20Styles/rgb-to-color.png)

Creates a **Color** value from red, green, blue channels. Numbers must be between [0-255] inclusive.

```
Utils.getColorRGB([NUMBER], [NUMBER], [NUMBER])
```

***

### Set Color

![set-color-block](http://static.stencyl.com/pedia2/block-images/9%20-%20Drawing/1%20-%20Styles/set-color.png)

Sets the color used in drawing shapes (does not apply to fonts). You can select the color using the color picker, drag in a color attribute or drag in any block that returns a color.

```
g.fillColor = [COLOR];
```

***

### Set Font

![set-font-block](http://static.stencyl.com/pedia2/block-images/9%20-%20Drawing/1%20-%20Styles/set-font-new.png)

Sets the font used in drawing text. You can pick the font directly or drag in a font attribute block.

```
g.setFont([FONT]);
```

***

## Opacity

### Set Opacity

![set-opacity-block](http://static.stencyl.com/pedia2/block-images/9%20-%20Drawing/1%20-%20Styles/set-alpha.png)

Sets the opacity (alpha) used in drawing to the specified percentage. Number must be between [0-100] inclusive.

```
g.alpha = ([NUMBER]/100);
```

***

## Stroke

### Set Stroke Color

![set-stroke-color-block](http://static.stencyl.com/pedia2/block-images/9%20-%20Drawing/1%20-%20Styles/set-stroke-color.png)

Sets the stroke color used when drawing shapes.

```
g.strokeColor = [COLOR];
```

***

### Set Stroke Thickness

![set-stroke-block](http://static.stencyl.com/pedia2/block-images/9%20-%20Drawing/1%20-%20Styles/set-thickness.png)

Sets the stroke thickness (width) used when drawing shapes. Set to 0 to disable.

```
g.strokeSize = [NUMBER];
```

***

## Font Width

### Get Width of Text for Current Font

![get-font-width-block](http://static.stencyl.com/pedia2/block-images/9%20-%20Drawing/1%20-%20Styles/get-font-width.png)

Returns the width of the specified text using the current font. Useful for calculating text drawing positions.

```
g.font.font.getTextWidth([TEXT])
```

***

### Get Width of Text for Specific Font

![get-font-width-block](http://static.stencyl.com/pedia2/block-images/9%20-%20Drawing/1%20-%20Styles/get-font-width2-new.png)

Returns the width of the specified text using the given font. Useful for calculating text drawing positions.

```
[FONT].font.getTextWidth([TEXT])
```

***

## Font Height

### Get Height for Current Font

![get-font-height-block](http://static.stencyl.com/pedia2/block-images/9%20-%20Drawing/1%20-%20Styles/get-font-height.png)

Returns the height of text using the current font. Useful for calculating text drawing positions.

```
g.font.getHeight()
```

***

### Get Height for Specific Font

![get-font-height-block](http://static.stencyl.com/pedia2/block-images/9%20-%20Drawing/1%20-%20Styles/get-font-height2-new.png)

Returns the height of text using the given font. Useful for calculating text drawing positions.

```
[FONT].getHeight()
```

***