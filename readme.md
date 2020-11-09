# kini

#### An atomic css utility library offering the absolute minimum, in a wide range of sizes.

<br>
The following properties are accessible via shorthand notation:


```
align-items
background-color
background-position
background-repeat
border
border-color
border-style
flex-direction
flex-wrap
height
justify-content
justify-items
line-height
margin
margin-bottom
margin-left
margin-right
margin-top
opacity
padding
padding-bottom
padding-left
padding-right
padding-top
text-align
text-decoration
text-decoration-line
text-decoration-style
text-decoration-thickness
text-transform
vertical-align
white-space
width
z-index
```


By example, the following classlist:
```html
<div class="w-100% h-100% m-10px pb-5px o-50% z-100 td-u tt-c">
```
Will result in the following utility classes being applied to your element:
```css
.w-100\% {width: 100%}
.h-100\% {height: 100%}
.m-10px {margin: 10px}
.o-0\.5 {opacity: 0.5}
.z-100 {z-index: 100}
.td-u {text-decoration: uppercase}
.tt-c {text-transform: center}
```


The value in the shorthand after the "-" char is eihter numeric (with a unit syntax following), or alphabetic (if value is enum). Refer to source `kini.css` file in this repo for details.




<br>
The following properties are accessible via non-normative shorthand notation:


`border-radius`


Example:
```
.radius-10px {border-radius: 10px}
```
<br>
The following properties are declarative, meaning the selector name is the same as the css property value:


```
box-sizing
color
cursor
display
font-family
font-size
font-style
font-weight
position
```
By example, the following classlist:
```html
<div class="content-box red pointer block monospace italic 700 18px absolute">
```
Will result in the following utility classes being applied to your element:
```css
.content-box {box-sizing: content-box}
.red {color: red}
.pointer {cursor: pointer}
.block {display: block}
.monospace {font-family: monospace}
.italic {font-style: italic}
.700 {font-weight: 700}
.\31 8px {font-size: 18px}
.absolute {position: absolute}
```
<br>
The following utility classes are combinatorial:


```
.fixed-fill
.absolute-fill
.absolute-centered
.bgi-contain
.bgi-cover
.bordered
.outlined
.flex-c-sa
.flex-c-se
.flex-c-sb
.flex-c-c
.flex-c-fs
.flex-c-fe
.flex-r-c
.flex-r-fs
.flex-r-sa
.flex-r-sb
.flex-r-fe
.flex-r-se
```
Examples:
```css
.bgi-contain {
        background-position: center center;
        background-size: contain;
        background-repeat: no-repeat;
        width: 100%;
        height: 100%;
     }
.bordered {
        border-color: silver;
        border-style: solid;
        border-width: 1px;
     }
.flex-r-sb {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
     }
```


<br>
For reference purposes, please use the commented `kini.css` source file in this repo.
