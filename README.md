<div align="center"><img width="1000" src="https://github.com/BroFox86/theme-espresso-soda-light/raw/master/logo.png">
</div>

This is a converted syntax theme for Visual Studio Code from 
the original [Soda Theme](https://github.com/buymeasoda/soda-theme) 
using [Yeoman generator](https://github.com/Microsoft/vscode-docs/blob/0.9.0/release-notes/latest.md#yo-code---streamlined-customizations-for-vs-code) and based on the Light+ (default) theme.
Also available <img src="https://github.com/BroFox86/theme-espresso-soda-solarized/raw/master/icon-small.png" width=16 height=16/> [Solarized Espresso Soda](https://marketplace.visualstudio.com/items?itemName=brofox86.theme-espresso-soda-solarized) which based on the default Solarized Light theme.


## Screenshots

![Screenshot](https://github.com/BroFox86/theme-espresso-soda-light/raw/master/screenshots/screenshot_01.png)
![Screenshot](https://github.com/BroFox86/theme-espresso-soda-light/raw/master/screenshots/screenshot_02.png)
![Screenshot](https://github.com/BroFox86/theme-espresso-soda-light/raw/master/screenshots/screenshot_03.png)

## Installation

This theme is available for free in the <img src="https://marketplace.visualstudio.com/favicon.ico" width=16 height=16/> [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=brofox86.theme-espresso-soda-solarized). 

### Activation

a) After install the theme, launch *Command Palette*

* <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> [macOS](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf): `⇧+⌘+P`
* <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> [Linux](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf): `Ctrl+P`
* <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> [Windows](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf): `Ctrl+P`

b) Type `theme` and choose `Preferences: Color Theme`, then select this theme from the list.

## For Less users

Theme is designed for use together with [better-less](https://marketplace.visualstudio.com/items?itemName=radium-v.better-less) in the Less syntax for properly highlighting. 

## Customization

You can customize the colours to your liking, overriding the ones provided by this theme or extending them. 
More info [here](https://code.visualstudio.com/docs/getstarted/theme-color-reference). 

For example, the code below in the config.json file *(Preferences > Settings)* will change the sidebar item text colour to black and make the CSS tag colour blue:

```
"workbench.colorCustomizations": {
    "sideBar.foreground": "#000000"
},
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "scope": "entity.name.tag.css",
      "settings": {
        "foreground": "#2F6F9F"
      }
    }
  ]
}
```

The scopes are identified by using *Command Palette > Developer: Inspect TM Scopes*.

## Inconsistencies?

It's impossible now to fully match to the original theme, because the scope colours in VSC aren't enough customizable as in Sublime Text or Textmate. Use customization if you prefer other colors instead of provided by this theme.

## Contribution

Report issues/bugs to the [issue tracker](https://github.com/BroFox86/theme-espresso-soda-light/issues).

## What is the icon theme on your screenshots?

I use [vscode-icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons).