# Change Log

## 3.0.0 (2018-06-16)
* Enhancement: Pug syntax highlighting is fully reworked with intend to reduce excessive amount of similar to each other blue colours
* Enhancement: Added CSS syntax support
* Enhancement: Updated Less support
* Enhancement: Added several new colours
* Other: Changed some colours to match to the original Espresso Soda syntax theme

## 2.2.0 (2018-05-23)
* Enhancement [SCSS]: Added appropriate colours to `@` and `%` prefixes
* Enhancement [SCSS]: Added the colour to `@extend value`
* Enhancement [SCSS]: Added colours to `.className` dots
* Other [SCSS]: Changed the support function colour (`darken()`, `rgba()` etc.)
* Fix [SCSS]: Fixed some wrong colours in several places such as the hex value colour after a variable: `$grey: #333`

## 2.1.0 (2018-04-13)
* Enhancement: Added SCSS support
* Enhancement [SCSS]: Added SCSS mixin color

## 2.0.0
* Fix [JS]: Reverted some scope colours
* Fix: Changed the `punctuation.definition.entity.css` colour to match to the original Espresso Soda syntax theme and added `punctuation.definition.entity.less` colour with last value from `punctuation.definition.entity.css`
* Enhancement [JS]: Added several scope colours to match to the original Espresso Soda syntax theme
* Enhancement [Less]: Added the `meta.property-value.less` colour to match to the original Espresso Soda syntax theme
* Other: Removed [better-less](https://marketplace.visualstudio.com/items?itemName=radium-v.better-less) extension from dependencies. It is optional now and recommended for Less users
* Other: Removed unused background declarations from the json file of the theme

## 1.0.0
* Fix: Changed the invalid character colour (the `invalid.illegal` scope)
* Enhancement [Less]: Added the [better-less](https://marketplace.visualstudio.com/items?itemName=radium-v.better-less) extension as dependence to improve Less syntax highlighting
* Enhancement [CSS/Less]: Added a few scope colours to match to the original Espresso Soda syntax theme
* Enhancement [CSS/Less]: Changed the CSS tag colour (the `entity.name.tag.css` scope) and the Less ampersand colour (the `punctuation.definition.entity.css` scope) to match to the original Espresso Soda syntax theme

## 0.1.0
Initial version