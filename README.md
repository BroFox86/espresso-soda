# Espresso Soda for VSC

This is a converted syntax theme for Visual Studio Code from 
the original [Soda theme](https://github.com/buymeasoda/soda-theme) 
using [Yeoman generator](https://github.com/Microsoft/vscode-docs/blob/0.9.0/release-notes/latest.md#yo-code---streamlined-customizations-for-vs-code) and based on the *Light+ (default)* theme. Also available <img src="https://raw.githubusercontent.com/BroFox86/theme-espresso-soda-solarized/master/icon.png" width=20 height=20/> [Solarized Espresso Soda](https://marketplace.visualstudio.com/items?itemName=brofox86.theme-espresso-soda-solarized) which based on the Solarized Light theme.

## Screenshots

![Screenshot](https://github.com/BroFox86/theme-espresso-soda-light/raw/master/screenshots/screenshot_01.png)
![Screenshot](https://github.com/BroFox86/theme-espresso-soda-light/raw/master/screenshots/screenshot_02.png)
![Screenshot](https://github.com/BroFox86/theme-espresso-soda-light/raw/master/screenshots/screenshot_03.png)

## Installation

This theme is available for free in the <img src="https://marketplace.visualstudio.com/favicon.ico" width=15 height=15/> [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=brofox86.theme-espresso-soda-light). After install the theme select it from the Command Palette > Preferences: Color Theme.

## Customization

You can customize the colours to your liking, overriding the ones provided by this theme or extending them. 
More info [here](https://code.visualstudio.com/docs/getstarted/theme-color-reference). 

For example, the code below in the config.json file (Preferences > Settings) will change the sidebar item text colour to black and make the CSS tag colour blue:

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

The scopes are identified by using the Command Palette > Developer: Inspect TM Scopes.

## What is the icon pack on your screenshots?

I use [vscode-icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons).