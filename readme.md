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
flex
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


The convention for said shorthand notation, by example:


```css
.m-10px {margin: 10px}
.mb-5px {margin-bottom: 5px}
.jc-c {justify-content: center}
.jc-sb {justify-content: space-between}
.o-50\% {opacity: 50%}
.z-100 {z-index: 100}
.td-u {text-decoration: underline}
.tt-c {text-transform: capitalize}
```


The following properties are accessible via non-normative shorthand notation:


`border-radius`


Example:
```
.radius-10px {border-radius: 10px}
```
The following properties are declarative, meaning the selector name is the same as the css property value:
```
box-sizing
color
cursor
display
font-family
font-style
font-weight
position
```
Examples:
```css
.content-box {box-sizing: content-box}
.red {color: red}
.pointer {cursor: pointer}
.block {display: block}
.monospace {font-family: monospace}
.italic {font-style: italic}
.700 {font-weight: 700 }
.absolute {position: absolute}
```


The following utility classes are combonatorial:
```
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
