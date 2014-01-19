# Bodensee Chrome Dev Tools Theme

Easy-to-read, configurable theme for Chrome Developer Tools

![](https://raw.github.com/patik/Bodensee-theme-devtools/master/screenshots/inspect-panel.png)

## Installation

### Mac OS X

Automatic:

```
cp ~/Library/Application\ Support/Google/Chrome/Default/User\ StyleSheets/Custom.css ~/Library/Application\ Support/Google/Chrome/Default/User\ StyleSheets/Custom_backup.css
curl -o ~/Library/Application\ Support/Google/Chrome/Default/User\ StyleSheets/Custom.css https://raw.github.com/patik/Bodensee-theme-devtools/master/Custom.css
```

Or manually copy <a href="https://raw.github.com/patik/Bodensee-theme-devtools/master/Custom.css" target="_black">Custom.css</a> to `~/Library/Application\ Support/Google/Chrome/Default/User\ StyleSheets/`

### Linux

Automatic:

```
cp ~/.config/chromium/Default/User\ StyleSheets/Custom.css ~/.config/chromium/Default/User\ StyleSheets/Custom_backup.css
curl -o ~/.config/chromium/Default/User\ StyleSheets/Custom.css https://raw.github.com/patik/Bodensee-theme-devtools/master/Custom.css
```

Or manually copy <a href="https://raw.github.com/patik/Bodensee-theme-devtools/master/Custom.css" target="_black">Custom.css</a> to `~/.config/chromium/Default/User\ StyleSheets/`

### Windows

1. Download <a href="https://raw.github.com/patik/Bodensee-theme-devtools/master/Custom.css" target="_black">Custom.css</a>
2. Browse to the `%LOCALAPPDATA%\Google\Chrome\User Data\Default\User StyleSheets\` folder in Explorer (or press `windowskey+r` and paste it in)
    * If the symbolic path `%LOCALAPPDATA%` doesn't automatically resolve, please see this [article](http://www.blogtechnika.com/what-is-application-data-folder-in-windows-7/)
3. Overwrite the existing `Custom.css` file there

## Features

1. Nicer colors
2. More readable line height
3. Easier to see the selected DOM elements
4. Simple to customize

## Customization

Easily customize this theme with Sass by changing the colors in the `_setting.scss` file.

## Thanks

This theme was forked from [Augus](https://github.com/Augus)' great [Readable-ChromeDevThemes](https://github.com/Augus/Readable-ChromeDevThemes).
