# Polymer::Paper::Rails

The Paper elements are a set of UI elements that implement the [material design system](http://www.google.com/design/spec/material-design/introduction.html).

Polymer-paper-rails gem brings polymer paper web components into your Rails project.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'polymer-paper-rails', :git => "git://github.com/vsimonian/polymer-paper-rails.git"
```

<!--- (not published to rubygems.org)
And then execute:

    $ bundle

Or install it yourself as:

    $ gem install polymer-paper-rails
-->

## Getting started

In order to use Polymer paper elements you need to have
`polymer`, `iron-elements`, and `neon-elements` installed in your project. Use [polymer-rails](https://github.com/alchapone/polymer-rails) gem for adding `polymer` to your Rails application,
[polymer-iron-rails](https://github.com/vsimonian/polymer-iron-rails) for `iron-elements`, and [polymer-neon-rails](https://github.com/vsimonian/polymer-neon-rails) for `neon-elements`.

```ruby
gem 'polymer-rails'
gem 'polymer-iron-rails', :git => "git://github.com/vsimonian/polymer-iron-rails.git"
gem 'polymer-neon-rails', :git => "git://github.com/vsimonian/polymer-neon-rails.git"
gem 'polymer-paper-rails', :git => "git://github.com/vsimonian/polymer-paper-rails.git"
```

After running `bundle install` require needed paper elements into your `application.html` manifest file.

    //= require polymer/polymer
    //= require paper-button/paper-button


Each component should be required only once. Thus if you've already required component that has dependencies, you don't need
to explicitly require any of dependencies, otherwise it will raise exception.

## Available elements

* [paper-behaviors](https://elements.polymer-project.org/elements/paper-behaviors)
* [paper-button](https://elements.polymer-project.org/elements/paper-button)
* [paper-checkbox](https://elements.polymer-project.org/elements/paper-checkbox)
* [paper-dialog](https://elements.polymer-project.org/elements/paper-dialog)
* [paper-dialog-behavior](https://elements.polymer-project.org/elements/paper-dialog-behavior)
* [paper-dialog-scrollable](https://elements.polymer-project.org/elements/paper-dialog-scrollable)
* [paper-drawer-panel](https://elements.polymer-project.org/elements/paper-drawer-panel)
* [paper-fab](https://elements.polymer-project.org/elements/paper-fab)
* [paper-header-panel](https://elements.polymer-project.org/elements/paper-header-panel)
* [paper-icon-button](https://elements.polymer-project.org/elements/paper-icon-button)
* [paper-input](https://elements.polymer-project.org/elements/paper-input)
* [paper-item](https://elements.polymer-project.org/elements/paper-item)
* [paper-material](https://elements.polymer-project.org/elements/paper-material)
* [paper-menu](https://elements.polymer-project.org/elements/paper-menu)
* [paper-progress](https://elements.polymer-project.org/elements/paper-progress)
* [paper-radio-button](https://elements.polymer-project.org/elements/paper-radio-button)
* [paper-radio-group](https://elements.polymer-project.org/elements/paper-radio-group)
* [paper-ripple](https://elements.polymer-project.org/elements/paper-ripple)
* [paper-slider](https://elements.polymer-project.org/elements/paper-slider)
* [paper-spinner](https://elements.polymer-project.org/elements/paper-spinner)
* [paper-styles](https://elements.polymer-project.org/elements/paper-styles)
* [paper-tabs](https://elements.polymer-project.org/elements/paper-tabs)
* [paper-toast](https://elements.polymer-project.org/elements/paper-toast)
* [paper-toggle-button](https://elements.polymer-project.org/elements/paper-toggle-button)
* [paper-toolbar](https://elements.polymer-project.org/elements/paper-toolbar)
* [paper-scroll-header-panel](https://elements.polymer-project.org/elements/paper-scroll-header-panel)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
