# Lesson 06 - CSS - Box Model

## Overview

The box model is fundamental to understanding how to create custom web layouts.

A great place to start learning about the CSS Box Model is with this [video here by Kevin Powell](https://www.youtube.com/watch?v=D_akuQHIPtg).


## Everything is Boxes

In an HTML document, every single element is considered a box. But boxes are like ogres (or onions) they have layers. 

![Box model](images/box-model-diagram-1.png)

These layers determine how elements are laid out in relation to one another.

You can always check an elements box model by inspecting the page and selecting that element, as seen below:

![Box model](./images/box-model-animation.gif)

## Layers of The Box Model

Each layer represents a different part of the element. Below will outline how much space each layer takes up, and how to check.

### Content

Content is the size of the actual *content* of the HTML element. It is the height and width of any given text or image.

![Content box](images/content-box.png)

![Content Highlight](images/content-highlight-1.png)

### Padding

The padding is the space between the content and the border.

![Padding box](images/padding-box.png)

![Padding visual](images/padding-image.png)

### Border

The border is a visible border that can be added around an element. By default, elements do not have borders and the size is 0.

![Border box](images/Border-box-1.png)

![Border image](images/Border-image.png)

### Margin

The margin is the space between the element's border and other elements' borders.

![Margin box](images/Margin-box.png)

![Margin image](images/margin-image.png)

Margins will overlap with one another, as seen below:

![Overlapping margins](images/Overlapping-margins.png)

## Box Sizing

When you set an elements width and height, by default you are setting the content box size:

![Setting width and height](images/setting-width-and-height.png)

![Content box sizing box](images/Content-box-size-box.png)

![Content box sizing image](images/content-box-size-image.png)

This can feel unintuitive, so we typically set our `box-sizing` property on all elements to `border-box`. 

```CSS
* {
    box-sizing: border-box;
}
```

This makes it so when we set our height and width, it is applied to the total height and width of the content, padding, and border combined:

![Height and width added to p tag](images/setting-width-and-height.png)

![Border box sizing box](images/box-of-border-box-size.png)

![Border box sizing image](images/image-of-border-box-size.png)

For a side by side comparison:

| Content Box Sizing                                             | Border Box Sizing                                               |
|----------------------------------------------------------------|-----------------------------------------------------------------|
| ![Content box sizing box](images/Content-box-size-box.png)     | ![Border box sizing box](images/box-of-border-box-size.png)     |
| ![Content box sizing image](images/content-box-size-image.png) | ![Border box sizing image](images/image-of-border-box-size.png) |
