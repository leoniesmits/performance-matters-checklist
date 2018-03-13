# Performance Checklist

## Table of Contents

*   [Miscellaneous](#miscellaneous)
*   [Audits](#audits)
*   [HTTP optimisation](#http-optimisation)
    *   [HTTP/1](#http1)
    *   [HTTP/2](#http2)
*   [Caching](#caching)
*   [Minification](#minification)
    *   [Images](#images)
    *   [CSS](#css)
    *   [HTML](#html)
    *   [JavaScript](#javascript)
    *   [Fonts](#fonts)
*   [Perceived Performance](#perceived-performance)
*   [Performance](#performance)
    *   [Images](#images-1)
    *   [CSS](#css-1)
    *   [HTML](#html-1)
    *   [JavaScript](#javascript-1)
    *   [Fonts](#fonts-1)
*   [Backend optimisation](#backend-optimisation)

## Miscellaneous

*   Tip: Different profile / user in Chrome without extensions
*   Add some more points here...

## Audits

*   Add some more points here...

## HTTP optimisation

*   Add some more points here...

### HTTP/1

*   Add some more points here...

### HTTP/2

*   Add some more points here...

## Caching

*   Add some more points here...

## Minification

*   Add some more points here...

### Images

*   Add some more points here...

### CSS

Minify CSS and put all styles in a single stylesheet.
This sample of code:
```CSS
html, body, div, span, applet, object, iframe, table, caption, tbody, tfoot, thead, tr, th, td, 
del, dfn, em, font, img, ins, kbd, q, s, samp, small, strike, strong, sub, sup, tt, var, 
h1, h2, h3, h4, h5, h6, p, blockquote, pre, a, abbr, acronym, address, big, cite, code, 
dl, dt, dd, ol, ul, li, fieldset, form, label, legend {
		vertical-align: baseline;
		font-family: inherit;
		font-weight: inherit;
		font-style: inherit;
		font-size: 100%;
		outline: 0;
		padding: 0;
		margin: 0;
		border: 0;
}


:focus {
		outline: 0;
}

input[type=submit] {
   -webkit-appearance: none;
}

html {
	overflow-x: hidden;
	overflow-y: scroll;
	max-width:   100%;
}

body {
	max-width:   100%;
	overflow-x: hidden;
	background: white;
	font-family: 'Open Sans', sans-serif;
	color: #676767;
	position: relative;
}
``` 
Will be converted to this: 
```CSS
html,body,div,span,applet,object,iframe,table,caption,tbody,tfoot,thead,tr,th,td,del,dfn,em,font,img,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,dl,dt,dd,ol,ul,li,fieldset,form,label,legend{vertical-align:baseline;font-family:inherit;font-weight:inherit;font-style:inherit;font-size:100%;outline:0;padding:0;margin:0;border:0}:focus{outline:0}input[type=submit]{-webkit-appearance:none}html{overflow-x:hidden;overflow-y:scroll;max-width:100%}body{max-width:100%;overflow-x:hidden;background:white;font-family:'Open Sans',sans-serif;color:#676767;position:relative}
```

This will save 198 bytes. Doing this for the entire site will improve the loading time.

### Source
[minifier](https://www.minifier.org/) does this for CSS and JS.
[more options here.](https://developers.google.com/speed/docs/insights/MinifyResources)

### HTML

*   Add some more points here...

### JavaScript

*   Add some more points here...

### Fonts

*   Add some more points here...

## Perceived Performance

*   Add some more points here...

## Performance

*   Add some more points here...

### Images

*   Add some more points here...

### CSS

*   Add some more points here...

### HTML

*   Add some more points here...

### JavaScript

*   Add some more points here...

### Fonts

*   Add some more points here...

## Backend optimisation

*   Add some more points here...
