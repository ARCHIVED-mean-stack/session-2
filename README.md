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

###SASS for responsive design of new navbar 
```
.hidden {
  display: none;
}

.options {
  text-align: center;
  padding: 2rem 0;
  select {
    margin-right: 2rem;
  }
}


.main-nav {
  background: #eee;
  margin-bottom: 1em;
  ul {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }
  a {
    padding: 1.25rem 0.5rem;
    font-size: 1rem;
    max-width: 140px;
    font-weight: bold;
    display: flex;
    align-items: flex-start;
    color: $reddish;
    background-color: $tan;
    &:hover, &:focus {
      background-color: $reddish;
      color: $white;
      svg {
        fill: $white; 
      }
      span {
        color: $white; 
      }
    }
  }
  span {
    display: block;
    font-size: 0.875rem;
    font-weight: normal;
    color: #888;
    margin: 0.25rem 0 0 0;
  }
  .icon {
    width: 40px;
    height: 40px;
    float: left;
    margin-right: 1rem;
    fill: #999;
  }
  &.outlines {
    * {
      outline: 1px solid rgba(red, 0.5); 
    }
  }
}

@media (min-width: $break-one) {
  .main-nav {
    a {
      max-width: 500px;
      font-size: 1.5rem; 
    }
    .icon {
      width: 25px;
      height: 25px;
    }
  }
}
```


##SVG
[The spec](https://developer.mozilla.org/en-US/docs/Web/SVG/Element) and Mozilla docs

`<use>` `<viewBox>`

https://icomoon.io

http://responsivelogos.co.uk

http://www.svgeneration.com/recipes/Beam-Center/

##Flex Box

https://css-tricks.com/snippets/css/a-guide-to-flexbox/


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


