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

Things to think about when using *fieber.css* as a foundation for your website:

* Classless frameworks come with a lot of limitations. Building a more advanced layout is up to you.
* This framework does not include a full-featured CSS reset. You may want to add styles, e.g. to remove the default `margin` of text elements.
* Right-to-left content is supported by adding `dir="rtl"` to the `<html>` tag.
* The current font stacks may not be perfect for writing systems like Arabic script.
* Remember to respect your users’ [motion preferences](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-motion) when adding animations. ([Example](https://github.com/csstools/sanitize.css/blob/main/reduce-motion.css))

There are many [other classless frameworks](https://www.cssbed.com) that may be better suited for your use case.

## Browser support

* Chrome 105 and newer
* Edge 105 and newer
* Opera 91 and newer
* Safari 15.4 and newer
* <del>Firefox</del> (see [`:has`](https://caniuse.com/css-has)) 🙈

## License

This software is licensed under the [MIT License](https://opensource.org/licenses/MIT).
