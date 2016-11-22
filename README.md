# hero-image-form
In this tutorial [Solodev](https://www.solodev.com/) will show how to use a form to your hero image section. Because of its key location, a hero image section is the ideal place for a form that can better direct the behavioral flow of a visitor. With this in mind, you can effectively direct the next steps of a website visitor with a simple form and call-to-action.

## Tutorial

For detailed instructions, view Solodev's [Adding a Form to your Hero Image](https://www.solodev.com/blog/web-design/adding-a-form-to-your-hero-image.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/8vqk6n8r/).

## HTML

The Hero Image Form contains the following HTML markup.

```
<div id="highlighted">
	<div id="search-form" class="container">
		<div class="row">
			<div class="col-sm-12">
				<div class="mod-search block">
					<h1 class="home-image">
						<img alt="WebCorpCo" class="img-responsive" src="https://www.solodev.com/assets/hero-form/logo.png">
					</h1>
					<h2 class="home-title">
						Start Your Next Project Today
					</h2>
					<div class="block-content">
						<form action="#" class="hero-form form-inline" id="hero-form" method="post" role="form">
							<div class="form-group">
								<label class="control-label sr-only" for="services-select">Choose Type of Service</label> 
									<select>
										<option value="">
											Choose Type of Service
										</option>
										<option value="marketing">
											Marketing
										</option>
										<option value="design">
											Design
										</option>
										<option value="programming">
											Programming
										</option>
										<option value="support">
											Support
										</option>
										<option value="training">
											Training
										</option>                                                       
									</select>
								<label class="control-label sr-only" for="email">Enter Email</label>
								<input id="email" class="form-control" name="email_search" placeholder="Enter Email" type="text">
								<input id="Get Started" class="form-control btn btn-lg btn-default btn-warning" type="submit" value="Get Started">
							</div>
						</form>
						<h3 class="home-title">
							<a href="#">Learn More About WebCorpCo&nbsp;<i class="fa fa-angle-double-right fa-lg" aria-hidden="true"></i></a>
						</h3>
					</div>
				</div>
			</div>
		</div>
	</div>
	<section class="heroimage-wrapper">
		<div class="heroimage">
			
		</div>
	</section>
</div>
```

## CSS

All required CSS is in hero-image-form.css


## External Includes

This tutorial contains the following third party resources.

```
<link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">

<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script type="text/javascript" src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
