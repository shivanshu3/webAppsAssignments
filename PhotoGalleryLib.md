# PhotoGalleryLib Documentation

## Introduction

This library contains some functions which will be helpful for completing the assignments for this course. It has functions for detecting screen size changes, creating image tables of various sizes, creating modals, etc.

The JavaScript file can be found [here](https://github.com/shivanshu3/webAppsAssignments/blob/master/PhotoGalleryLib.js).

Simply add a `<script>` tag like the following to use this in your code:

`<script src="https://raw.githubusercontent.com/shivanshu3/webAppsAssignments/master/PhotoGalleryLib.js"></script>`

## Functions

- `PhotoGalleryLib.onSizeClassChange (callback)`

    This function is used for detecting screen size changes. This function takes a callback as an argument, which is called whenever the screen size is changed. One of the strings "small", "medium", or "large" will be passed as an argument to the callback function when the screen size is changed. Note that the callback function will only be called when the screen size changes from one size class to another (ex, small to medium). It will not be called repeatedly while the screen size is being changed within a particular size class like large.

- `PhotoGalleryLib.generateGrid (imageUrls, size)`

    This function is used for generating a table DOM element which can be used to display a grid of images. The `imageUrls` argument is an array of image URLs which are supposed to be displayed in the table. These can be relative URLs like './images/foo.jpg' or even http URLs. The `size` argument can be one of "small", "medium", or "large". a 1x8 grid is made for small screen sizes, a 2x4 grid is made for medium screen sizes, and a 4x2 grid is made for large screen sizes.

- `PhotoGalleryLib.createModal ()`

    This function creates a modal which can be used for presentation mode. There will be no visible effect when this function is called since the modal is closed by default. You can however inspect the DOM tree in your browser to see that a new `<div>` gets inserted into the body which has a CSS attribute `display:none`.

- `PhotoGalleryLib.initModal`

    foo bar

- `PhotoGalleryLib.closePresentationModal`

    foo bar

- `PhotoGalleryLib.openPresentationModal`

    foo bar
    
- `PhotoGalleryLib.setModalImgSrc`

    foo bar
    
- `PhotoGalleryLib.addImageClickHandlers`

    foo bar
