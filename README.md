# HTML5 CSS Plugin 

<p align="center"><img alt="HTML5 CSS Plugin logo" src="logo/logo.png" /></p>

>plugins: marquee

This is a (deprecated) `<marquee></marquee>` tag implementation in HTML5 using pure CSS3 animations. Please see [**live demo here**](http://muchweb.github.io/html5-marquee/).

## Installation

- Bower: `bower install html5-marquee`
- NPM: `npm install html5-marquee`

## Usage

### Simple usage:

```html
<div class="marquee" data-marquee="Text contents"></div>
```

### Adjust marquee speed:

|CSS Class|Delay|
|:---:|:---:|
|`.marquee-speed-drowsy`|`30s`|
|`.marquee-speed-slow`|`20s`|
|`.marquee-speed-normal`|`10s` (default)|
|`.marquee-speed-fast`|`7s`|
|`.marquee-speed-swift`|`5s`|
|`.marquee-speed-hyper`|`2s`|

#### Custom speed:

Inherits the speed from the class or inline style

|CSS Class|Delay|
|:---:|:---:|
|`.marquee-speed-custom`|`inherit`|

### Adjust direction:

|CSS Class||
|:---:|:---:|
|`.marquee-direction-left`|Right to left (default)|
|`.marquee-direction-right`|Left to right|
|`.marquee-direction-alternate`|Alternate movement|

### Adjust direction:

|CSS Class||
|:---:|:---:|
|`.marquee-direction-left`|Right to left (default)|
|`.marquee-direction-right`|Left to right|
|`.marquee-direction-alternate`|Alternate movement|

### Vintage effect:

|CSS Class||
|:---:|:---:|
|`.marquee-movement-smooth`|Smooth animation (default)|
|`.marquee-movement-steps20`|Jamming animation|
|`.marquee-movement-steps10`|Jamming animation|

## Building

Requirements:

 - Node.js
 - NPM

```bash
make
```
 - normal:
	lessc marquee.less marquee.css
 - compress:
	lessc -x marquee.less marquee.css
 - prefix:
	lessc marquee.less --autoprefix="> 0.01% in CN" marquee-prefix.css


