# What is Flexbox?
* Flexbox make life easier
* no floats
* It is responsive and mobile friendly
* media queries make it even better
* positioning child elements is much easier
* their [margins don't collapse](https://medium.com/@joseph0crick/margin-collapse-in-css-what-why-and-how-328c10e37ca0) with the margins of their contents

## Flexible box model concept
* the ability to alter item width and height to best fit in its containers available free space
* flexbox is direction-agnostic
* built for small-scale layouts while CSS grid is for more large scale

## How flexbox layout works
![flexbox layout](https://i.imgur.com/3lXasBZ.png)

* We designate the flex container as `display: flex`
* Inside that we have child items (flex items)
* x and y axis (flex calls this main axis and the cross axis)

## Flex properties
* display: flex | inline-flex (container)
* flex-wrap: wrap | nowrap | wrapreverse
* flex-basis: `<length>` (similar to width)
* justify-content: flex-start | flex-end | center
* align-self: flex-start | flex-end | center
* align-items: flex-start | flex-end | center
* align-content: flex-start | flex-end | center
* flex-grow: `<number>`
* flex-shrink: `<number>`
* flex: `<integer>`
* order: `<integer>`

`$ git checkout 02-flexbox-side-by-side`
