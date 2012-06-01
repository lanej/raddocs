[![Travis status](https://secure.travis-ci.org/oestrich/raddocs.png)](https://secure.travis-ci.org/oestrich/raddocs)


# Raddocs

Raddocs is a browser for JSON outputted by the [rspec_api_documentation](http://github.com/zipmark/rspec_api_documentation) gem.

## Install

`Gemfile`

	gem 'raddocs'

`config/routes.rb`

	...
	match "/docs" => Raddocs::App, :anchor => false
	...