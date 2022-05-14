# Neumorphism_Checkbox
一Neumorphism checkbox design for OpenHarmony.

## Download & Install

Install using npm

```npm i hmos-neumorphism ```
Details about OpenHarmony NPM environment configuration, see at [here](https://gitee.com/openharmony-tpc/docs/blob/master/OpenHarmony_npm_usage.md)

## Usage Instructions
# Note :

Add this css snippet when passing input or button through slot .

```css
button, input{
    width: 100%;
    height: 100%;
    background-color:transparent;
    color: black;
}
```

# Checkbox

<img src="sample_images/checkbox.png" width="" height="">

Import:
```html
<element name='neucheckbox' src='hmos-neumorphism/checkbox/checkbox.hml'></element>
```

Usage:
```html
<neucheckbox color="" width="50px" height="50px" border="50px" checked="true" @check-event="checkboxClick"></neucheckbox>
```

# Radio

<img src="sample_images/radio.png" width="" height="">

Import:
```html
<element name='neuradio' src='hmos-neumorphism/radio/radio.hml'></element>
```

Usage:
```html
<neuradio width="50px" color="" height="50px" border="50px" checked="" @check-event="radioClick"></neuradio>
```

# Switcher

<img src="sample_images/switcher.png" width="" height="">

Import:
```html
<element name='neuswitcher' src='hmos-neumorphism/switcher/switcher.hml'></element>
```

Usage:
```html
<neuswitcher width="60px" color="" height="30px" border="50px" toggle="off" @toggle-event="toggleClick"></neuswitcher>
```

## Compatibility
Supports OpenHarmony API version 6 

## Directory Structure
````
|---- Neumorphism  
|     |---- entry  # sample app usage
|     |---- Neumorphism  # Neumorphism library
|           |---- checkbox  # Checkbox Component
|                 |---- checkbox.css  # Checkbox style component
|                 |---- checkbox.hml  # Checkbox hml file
|                 |---- checkbox.js  # Checkbox JS
|           |---- radio  # Radio Component
|                 |---- radio.css  # Radio style component
|                 |---- radio.hml  # Radio hml file
|                 |---- radio.js  # Radio JS
|           |---- switcher  # Switcher Component
|                 |---- switcher.css  # Switcher style component
|                 |---- switcher.hml  # Switcher hml file
|                 |---- switcher.js  # Switcher JS
|     |---- README.MD  # installation and usage                   
````
## Code Contribution
If you find any problems during usage, you can submit an [Issue](https://gitee.com/openharmony-sig/Checkbox/issues) to us. Of course, we also welcome you to send us [PR](https://gitee.com/openharmony-sig/Checkbox/pulls).

## Open source License
This project is based on [Apache License 2.0](https://gitee.com/openharmony-sig/Checkbox/blob/master/LICENSE.txt) ，please enjoy and participate in open source freely.

# Reference:

<a href="https://neumorphism.io/">neumorphism.io</a>

<a href="https://ismail9k.github.io/neomorphism/">ismail9k.github.io/neomorphism</a>
