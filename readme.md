# [cssprettifier userscript](http://userscripts.org/scripts/show/162004)

[Userscript](http://wiki.greasespot.net/User_script) to format and syntax highlight CSS files you open

![screenshot](screenshot.png)


### Before

```css
.callout{margin:15px 0;padding:10px;font-size:13px;color:#8d8d6d;background:#fffef1;border:1px solid #e5e2c8;border-radius:4px;}.callout strong{font-weight:bold;color:#000;}.callout h2{margin:0;font-size:16px;font-weight:300;}.callout p:last-child{margin-bottom:0;}
```

### After

```css
.callout {
    margin: 15px 0;
    padding: 10px;
    font-size: 13px;
    color: #8d8d6d;
    background: #fffef1;
    border: 1px solid #e5e2c8;
    border-radius: 4px;
}

.callout strong {
    font-weight: bold;
    color: #000;
}

.callout h2 {
    margin: 0;
    font-size: 16px;
    font-weight: 300;
}

.callout p:last-child {
    margin-bottom: 0;
}
```

Powered by [cssbeautify](https://github.com/senchalabs/cssbeautify) and [Prism](http://prismjs.com).


# License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
(c) [Sindre Sorhus](http://sindresorhus.com)
