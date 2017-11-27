# eleganttip.css&nbsp;&nbsp;[![GitHub release](https://img.shields.io/github/release/gw19/eleganttip.css.svg)](https://github.com/gw19/eleganttip.css/releases)
Provide a simple and elegant tips message (tooltips) on your element with pure CSS.
<br>
<br>
## Installation
Including eleganttip.css or eleganttip.min.css in your html file.<br>
```html
<link rel='stylesheet' href='eleganttip.css'>
```
or
```html
<link rel='stylesheet' href='eleganttip.min.css'>
```
## Usage
### The easiest way
Adding the class "et" in the tag of element in which you want to display the tips on.<br>
E.g. if you want to show the tips message on a button,<br>
```html
<button type='submit' class='btn et'>hover me</button>
```
then creating a child element ```<span>``` with adding one of the following in its class:
* et-bottom
* et-top
* et-left
* et-right
  
and write messages into ```<span>```, e.g.
```html
<button type='submit' class='btn et'>hover me
  <span class='et-top'>
    here you are!
  </span>
</button>
```
  
