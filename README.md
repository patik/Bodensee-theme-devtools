## Bodensee Chrome Dev Tools Theme

An easy-to-read, configurable theme for Chrome Developer Tools.

![](https://raw.github.com/patik/Readable-ChromeDevThemes/master/screenshots/inspect-panel.png)

### Installation

#### Mac OS X

```
cp ~/Library/Application\ Support/Google/Chrome/Default/User\ StyleSheets/Custom.css ~/Library/Application\ Support/Google/Chrome/Default/User\ StyleSheets/Custom_backup.css
curl -o ~/Library/Application\ Support/Google/Chrome/Default/User\ StyleSheets/Custom.css https://raw.github.com/patik/Readable-ChromeDevThemes/master/Custom.css
```

Or download <a href="https://raw.github.com/patik/Readable-ChromeDevThemes/master/Custom.css" target="_black">Custom.css</a> and copy it to `~/Library/Application\ Support/Google/Chrome/Default/User\ StyleSheets/`

#### Linux

```
cp ~/.config/chromium/Default/User\ StyleSheets/Custom.css ~/.config/chromium/Default/User\ StyleSheets/Custom_backup.css
curl -o ~/.config/chromium/Default/User\ StyleSheets/Custom.css https://raw.github.com/patik/Readable-ChromeDevThemes/master/Custom.css
```

Or download <a href="https://raw.github.com/patik/Readable-ChromeDevThemes/master/Custom.css" target="_black">Custom.css</a> and copy it to `~/.config/chromium/Default/User\ StyleSheets/`

#### Windows

1. Download <a href="https://raw.github.com/patik/Readable-ChromeDevThemes/master/Custom.css" target="_black">Custom.css</a>
2. Browse to the `%LOCALAPPDATA%\Google\Chrome\User Data\Default\User StyleSheets\` folder
3. Overwrite the existing `Custom.css` file there

If the symbolic path `%LOCALAPPDATA%` doesn't automatically resolve, please see this [article](http://www.blogtechnika.com/what-is-application-data-folder-in-windows-7/).

### Features ###
1. Nicer colors
2. More readable line height
3. Easier to see the selected DOM elements
4. Simple to customize

### Customization ###
Easily customize this theme with Sass by changing the colors in the `_setting.scss` file.

### Thanks

This theme was forked from [Augus](https://github.com/Augus)' great [Readable-ChromeDevThemes](https://github.com/Augus/Readable-ChromeDevThemes).
