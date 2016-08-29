# Minimal App Promo Template

![Template Preview](https://github.com/jchaike/minmalAppTemplate/raw/master/preview.gif "Template Preview")

Live example [here](https://jchaike.github.io/minmalAppPromoTemplate/dist/)

You can see a live site example [here](http://www.onemoresong.io)

## Optional Dependencies

If you wish to modify the template from the source, it requires `npm` and `gulp`.

Run `npm install` to install all dependencies.

Make sure to run `npm install -g gulp browser-sync`


## Usage

You can customize the device on the template by using the appropriate class names and class colors, with a Windows device being the exception.

```html
<div class="device android black">
<div class="device android white">
<div class="device iphone black">
<div class="device iphone white">
<div class="device windows default">
```

Replace your screen shot with `images/screenshot.png` (750 × 1334).


## Run Locally

Simply run `gulp` to compile, and start a local server on `localhost:3000`

## Build

A compiled version of the site is included in `dist` however, if you would like to make additional changes, I would recommend making them in the `src` folder, which can be easily compiled with `gulp build`. If you are already running `gulp` then you do not need to run `gulp build` separately.


## Support

This template comes with no additional support. Feel free to modify it and improve it as needed. Pull requests are appreciated.
