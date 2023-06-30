# Image Slider

The Image Slider is a responsive web component that allows you to display a slideshow of images with a navigation bar. It provides an engaging way to showcase multiple images in a compact and visually appealing manner.

## Preview

You can see a live preview of the Image Slider [here](https://shiba-tatsuya.github.io/image-slider/).

## HTML Structure

The HTML structure of the Image Slider consists of the following elements:

- `<section class="container">`: This is the container that wraps the entire slider component.
- `<div class="slider-wrapper">`: This div serves as a wrapper for the slider and navigation bar.
- `<div class="slider">`: This div contains the images that will be displayed in the slider. Add your own images by updating the `src` attribute of the `<img>` tags.
- `<div class="slider-nav">`: This div represents the navigation bar for the slider. Each `<a>` tag corresponds to a slide and includes an `href` attribute that links to the respective slide.

## CSS Styles

The CSS file (`style.css`) contains the styles that control the appearance and behavior of the Image Slider. Here are the main CSS classes used:

- `.container`: Defines the styling for the container section that holds the slider component.
- `.slider-wrapper`: Positions the slider and navigation bar within the container and sets a maximum width.
- `.slider`: Controls the display and scroll behavior of the slider. Adjusts the aspect ratio and applies a box shadow for visual effect.
- `.slider-nav`: Styles the navigation bar and positions it at the bottom center of the slider.
- `.slider-nav a`: Defines the styles for each navigation dot in the navigation bar. Changes the opacity on hover for interactivity.

## Compatibility

The Image Slider is compatible with modern web browsers and has been tested on the following browsers:

- Google Chrome
- Mozilla Firefox
- Safari
- Microsoft Edge

Please note that older browsers may not support some of the CSS properties used in the slider, and the appearance and functionality may vary.

