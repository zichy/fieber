# fieber.css

fieber.css is a *classless* and *accessible* CSS framework. It combines semantic markup with minimalist, brutalist, and opinionated styles.

Check out the [**demo site**](https://fieber.hack.re).

## Features

* Based on semantic HTML5 💕
* Accessibility-first approach 💪
* Supports every modern HTML element 🌎
* Responsive layout 🖥📱
* Light/dark theme 🌞🌚
* Written in vanilla CSS 🍦
* Just 17 kB unminified 🤏
* Easily customizable 🔧
* Print styles included 🖨
* RTL-ready 👈

## Usage

Download the `fieber.css` file and insert it into the `<head>` of your website:

```html
<link rel="stylesheet" href="fieber.css">
```

A npm package may come in the future.

## Customization

You can easily change the basic appearance like text and colors by adjusting the [custom properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties).

Things to keep in mind when using *fieber.css*:

* Classless frameworks come with a lot of limitations. Using them as a starting point for a more complex website with lots of class-based stylings may be a bad choice.
* This framework does not include a full-featured CSS reset, e.g. most default `margin` values are kept.
* Please ensure an [adequate contrast](https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html) when using custom colors.
* Right-to-left content is supported by adding `dir="rtl"` to the `<html>` tag.
* The current font stacks may not be perfect for writing systems like Arabic script.
* Remember to respect your users’ [motion preferences](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-motion) when adding animations. ([Example](https://github.com/csstools/sanitize.css/blob/main/reduce-motion.css))

There are many [other classless frameworks](https://www.cssbed.com) that may be better suited for your specific use case.

## Browser support

* Chrome 105 and newer
* Edge 105 and newer
* Opera 91 and newer
* Safari 15.4 and newer
* Firefox 121 and newer

## License

fieber.css is licensed under the [MIT License](https://opensource.org/licenses/MIT).

The example video is from *Big Buck Bunny* by the Blender Foundation ([CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)).
