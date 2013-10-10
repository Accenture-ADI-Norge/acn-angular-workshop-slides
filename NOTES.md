#Notes

##First:
1. `npm install`
2. `bower install` 
3. `grunt server`
Boom! Frontend.

##Lets get to know bootstrap. 
Implement navigation:

	<div class="navbar navbar-default navbar-static-top">
	  <div class="navbar-header">    
          <a class="navbar-brand" href="#">AAFW</a>
      </div>
		
	  <div class="collapse navbar-collapse header-collapse">
		  <ul class="nav navbar-nav">
			  <li>
				<a href="/">Nav Item 1</a>
			  </li>
			  <li>
				<a href="#">Nav Item 2</a>
			  </li>
			</ul>
		</div>
	</div>

Lets make it mobile. Inside `<div class="navbar-header">`:

	<button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".header-collapse">
		<span class="sr-only">Toggle navigation</span>
		<span class="icon-bar"></span>
		<span class="icon-bar"></span>
		<span class="icon-bar"></span>
	  </button>

##BOWER
[bower-logo.png]
	
> [Bower](www.bower.io) is a package manager for the web. It offers a generic, unopinionated solution to the problem of front-end package management

> Bower runs over Git, and is package-agnostic. A packaged component can be made up of any type of asset, and use any type of transport (e.g., AMD, CommonJS, etc.).

Lets try it:

	bower install bootstrap-theme-white-plum
	
And add the new bootstrap.css in `bower_components/bootstrap-theme-white-plum/dist/css` to your index.html.