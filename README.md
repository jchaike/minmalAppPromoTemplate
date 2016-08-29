# Minimal App Template

![Template Preview](https://github.com/jchaike/minmalAppTemplate/raw/master/preview.gif "Template Preview")

You can see a live example [here](https://www.onemoresong.io)

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

## Run Locally

Simply run `gulp` to compile, and start a local server on `localhost:3000`

## Build

If you make any changes in `src` you can easily compile them into the `dist` folder by running `gulp build`

## Support

This template comes with no additional support. Feel free to modify it and improve it as needed. Pull requests are appreciated.
