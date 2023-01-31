# CHANGELOG

## v0.4.5

* Fix `undefined method [] for Pry::Prompt:Class (NoMethodError)` error when entering rails console

## v0.4.4

* Fix deprecation warning `Module#parent_name` in Rails 6.x

## v0.4.3

* Fix my stupid mistake on v0.4.2: Require hirb-unicode-steakknife as hirb-unicode

## v0.4.2 [DO NOT USE]

* Require hirb-unicode-steakknife as unicode-steakknife
* BUG: The require name was wrong

## v0.4.1 [DO NOT USE]

* Replace `hirb-unicode` with `hirb-unicode-steakknife` in optional enhancement. (Run `rails generate awesome_rails_console:install` to install them)
* BUG: It doesn't require properly

## v0.4.0

* Add `pry-byebug`, `pry-stack_explorer` and `hirb` back as optional enhancement. (Run `rails generate awesome_rails_console:install` to install them)

## v0.3.0

* Remove `pry-byebug`, `pry-stack_explorer` and `hirb` dependency. Please add them into your application `Gemfile` if you still want to use.
* Remove color indicator from prompt.

## v0.2.1

* No changes in functionality. Release for updating information on rubygems.org.

## v0.2.0

* Remove Ruby 1.9 support.

## v0.1.0

* First release.
