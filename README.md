#iOS Device SVG Templates

##iPhone 5c

![screenshot](http://f.cl.ly/items/3Y3S180Z3k1n270N1W0p/ios-device-svg-templates-screenshot.png)

###Themes

- iphone-5c-green (default)
- iphone-5c-blue
- iphone-5c-yellow
- iphone-5c-red
- iphone-5c-white

###Usage

- Viewport is sized to work with screenshots taken from the iPhone 5, 5s, 5c and the iPhone Simulator (640 ✕ 1136 portrait, 1136 ✕ 640 landscape).

```html
<object type="image/svg+xml"
    data="iphone-5c-portrait.svg?screenshot=neo-geek.net-portrait.png"></object>
<object type="image/svg+xml"
    data="iphone-5c-landscape.svg?screenshot=neo-geek.net-landscape.png"></object>
```

With theme specified:

```html
<object type="image/svg+xml"
    data="iphone-5c-portrait.svg?screenshot=neo-geek.net-portrait.png&amp;theme=iphone-5c-red"></object>
<object type="image/svg+xml"
    data="iphone-5c-landscape.svg?screenshot=neo-geek.net-landscape.png&amp;theme=iphone-5c-red"></object>
```

###Converting to Static PNG With ImageMagick

```bash
composite -background transparent -geometry +80+251 screenshot-portrait.png iphone-5c-portrait.svg'[800x1640]' output.png
composite -background transparent -geometry +251+80 screenshot-landscape.png iphone-5c-landscape.svg'[1640x800]' output.png
```