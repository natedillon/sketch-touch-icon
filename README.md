# sketch-touch-icon

A touch icon template for [Sketch](http://bohemiancoding.com/sketch/).

## Instructions

1. Open the `touch-icon.sketch` file in Sketch.
1. Add your custom icon to the artboards, which are each set to the specific sizes used for touch icons.
1. Click “File > Export…” to export the icons. Choose your location and “Save”. It should save all the icons with the correct file name.

To add the icons to your HTML document, add the following code to the `<head>`:

```
<link rel="icon" sizes="192x192" href="touch-icon-192x192.png">
<link rel="apple-touch-icon-precomposed" sizes="180x180" href="apple-touch-icon-180x180-precomposed.png">
<link rel="apple-touch-icon-precomposed" sizes="152x152" href="apple-touch-icon-152x152-precomposed.png">
<link rel="apple-touch-icon-precomposed" sizes="144x144" href="apple-touch-icon-144x144-precomposed.png">
<link rel="apple-touch-icon-precomposed" sizes="120x120" href="apple-touch-icon-120x120-precomposed.png">
<link rel="apple-touch-icon-precomposed" sizes="114x114" href="apple-touch-icon-114x114-precomposed.png">
<link rel="apple-touch-icon-precomposed" sizes="76x76" href="apple-touch-icon-76x76-precomposed.png">
<link rel="apple-touch-icon-precomposed" sizes="72x72" href="apple-touch-icon-72x72-precomposed.png">
<link rel="apple-touch-icon-precomposed" href="apple-touch-icon-precomposed.png">
```

## Credits

For more information about touch icons, read [“Everything you always wanted to know about touch icons”](https://mathiasbynens.be/notes/touch-icons).

Copyright © 2015 D. Nathan Dillon ([natedillon.com](http://natedillon.com))
