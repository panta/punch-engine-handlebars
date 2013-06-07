# Handlebars Template Engine for Punch 

Use this plugin to replace Punch's default Mustache template engine with [Handlebars](http://handlebarsjs.com). 

If present, [Swag](https://github.com/elving/swag) is used to provide useful Handlebars helpers.

### How to Setup

* Install the package
	
		npm install punch-engine-handlebars-swag

Please note that this is a temporary package, published as a stop-gap solution while waiting for the
Swag support to be merged upstream (see the [pull request](https://github.com/laktek/punch-engine-handlebars/pull/2)).

* Open your Punch project's configurations (`config.json`) and add the following:

		"plugins": {
			
			"template_engine": "punch-engine-handlebars-swag"

		}

* Now you can use Handlebars syntax for your project's templates. 

	Make sure you **save the templates with `.handlebars` extension**.


