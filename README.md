# ClientSideValidations-MongoMapper #

[![Build Status](http://travis-ci.org/dockyard/client_side_validations-mongo_mapper.png)](http://travis-ci.org/dockyard/client_side_validations-mongo_mapper)

[MongoMapper](https://github.com/jnunemaker/mongomapper) plugin for [ClientSideValidations](https://github.com/bcardarella/client_side_validations)

## Installation ##

In your Gemfile add the following:

```ruby
gem 'mongo_mapper'
gem 'client_side_validations'
gem 'client_side_validations-mongo_mapper'
```

Order matters here. `MongoMapper` and `ClientSideValidations` need to be
required **before** `ClientSideValidations-MongoMapper`.

[Follow the remaining installation instructions for ClientSideValidations](https://github.com/bcardarella/client_side_validations/README.markdown)

## Authors ##

[Brian Cardarella](http://twitter.com/bcardarella)

## Versioning ##

This gem follows [Semantic Versioning](http://semver.org)

Major and minor version numbers will follow `MongoMapper`'s major and
minor version numbers. For example,
`client_side_validations-mongo_mapper-0.10.0` will be compatible with
`~> mongo_mapper-0.10.0`

## Want to help? ##

Stable branches are created based upon each minor version. Please make
pull requests to specific branches rather than master.

Please make sure you include tests!

Unles Rails drops support for Ruby 1.8.7 we will continue to use the
hash-rocket syntax. Please respect this.

Don't use tabs to indent, two spaces are the standard.

## Legal ##

[DockYard](http://dockyard.com), LLC &copy; 2012

[@dockyard](http://twitter.com/dockyard)

[Licensed under the MIT license](http://www.opensource.org/licenses/mit-license.php)
