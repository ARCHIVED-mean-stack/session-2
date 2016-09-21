#MEAN Session Two

Python Simple Server `python -m SimpleHTTPServer <port>`

##SASS

* comments
* error checking
* variables
* imports and structure

[Bootstrap SASS](https://github.com/twbs/bootstrap-sass)

##Responsive

* Mobile first design
* Use min-width media queries to add features to larger screens `@media (min-width: 46.25em) { }`
* Use the meta tag to ensure this works on devices: [Viewport Demo](http://daniel.deverell.com/css-files/responsive-meta-example.zip)

##Second Page

###Static Pages
* static app - anchor in browser > request to server > database > html > browser
* AJAX - ability to refresh data after the app is running (mapquest vs google maps)
* Progressive enhancement - a trap?
* Spaghetti Javascript - code modifies existing DOM vs code that creates the DOM
* Mobile native (receives json) vs browser native (receives html)

###Thick client
* Modern web architecture - browser requests html > page contains JS that builds the base structure > ajax loads content via json > JS modifies DOM to present content.
* Benefits - same code for mobile and web, performance leverages the client (distributed), standardization on JS, html and css, speed and increased modularity.
* Routing

```
<body class="p-cuisines">

<li><a class="t-cuisines" href="#">Cuisines</a></li> 
<li><a class="t-recipes" href="#">Recipes</a></li>

.p-cuisines .t-cuisines { 
	color: #fff; 
	background:#600; 
} 
```

##Google font

```
@import url('http://fonts.googleapis.com/css?family=Lato:300,400,700');
$font-family: 'Lato', sans-serif;
```

##Homework

1. 

##Reading
Ethan Marcotte - [Responsive Web Design](https://abookapart.com/products/responsive-web-design)
Dan Cederholm - [SASS for Web Designers](https://abookapart.com/products/sass-for-web-designers)
