# layout

## Icon

![](img/3-3-9-img-01.png)

## Description

The layout subclass implements a container layer in the touch screen. The layout subclass is a subclass of UIWidget.
The control provides methods to set the layer container's clip, width and height, background color opacity, fill color, picture resources and other attributes.

##常规属性

请查看[git tongyongye](./../)

## Feature

![](img/3-3-9-img-02.png)
 


### backfround Color Opacity

Sets the opacity of the background color，ranging from 0-255, 0 for transparent, and 255 for the opaque option.

### Fill Color


- No color    
Sets no color for the background color.
- Monochrome   
Sets the background color（RGB).
- GradientColor   

	1.  StartColor  
	Sets the starting color of the gradient.
	2.  EndColor  
	Sets the ending color of the gradient.
	3.  X  
	X Vector
	4.  Y  
	Y Vector

### Clip

Hides control's child controls, which are out of the display area.


### File

Sets a picture (png, jpg) that will be displayed with default status.