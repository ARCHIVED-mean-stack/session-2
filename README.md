#MEAN Session Two

Python Simple Server `python -m SimpleHTTPServer <port>`

##SASS

* error checking - whatch out for this
* variables - add padding
* imports and structure

[Bootstrap SASS](https://github.com/twbs/bootstrap-sass)

##Responsive

* Mobile first design
* Use min-width media queries to add features to larger screens `@media (min-width: 46.25em) { }`
* Use the meta tag to ensure this works on devices: [Viewport Demo for Phone](http://daniel.deverell.com/css-files/responsive-meta-example/)

```
.info {
	position: static;
	width: 100%;
	background-color: $tan;
	padding: .5em;
	border: 1px solid #600;
	font-size: 0.875rem;

	th {
		text-align: left;
	}

	@media (min-width: 46.25em) {
		position: absolute;
		top: 0;
		left: -12rem;
		width: 10em;
	}
}


article {
	margin-left: 1em;
	position: relative;
	@media (min-width: 46.25em) {
		margin: 2em 0 0 12em;
	}
}
```

##SVG
https://developer.mozilla.org/en-US/docs/Web/SVG/Element

<use>

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

Chris Coyier - [Practical SVG](https://abookapart.com/products/practical-svg)


