# bulma-clean-theme

[![Gem Version](https://badge.fury.io/rb/bulma-clean-theme.svg)](https://badge.fury.io/rb/bulma-clean-theme)
![Gem](https://img.shields.io/gem/dt/bulma-clean-theme.svg)

This is a clean and simple Jekyll Theme built with the [Bulma](https://bulma.io/) framework, providing a modern-looking site to start with. 

The theme uses [Alpine.js](https://github.com/alpinejs/alpine) for its interactive components, such as mobile navbar and notifications.

## Contents

* [Installation](#installation)
* [Documentation](#documentation)
* [Upgrading to v1](#upgrading-to-v1)
* [Contributing](#contributing)
* [Development](#development)
* [Licence](#licence)


## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "bulma-clean-theme"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: bulma-clean-theme
```

If you are deploying to GitHub pages, then you can also install the [GitHub Pages gem](https://github.com/github/pages-gem) and use `remote_theme` instead of `theme` in your `_config.yml`. **Note that the GitHub Pages gem requires Jekyll version 3.9.**

```yaml
# With GitHub Pages Gem
remote_theme: chrisrhymes/bulma-clean-theme
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install bulma-clean-theme

## Documentation

Check out the demo site for the [Documentation](https://www.csrhymes.com/bulma-clean-theme/docs/)

## Upgrading to v1

There are several breaking changes for v1. Please read the [upgrade guide](https://www.csrhymes.com/bulma-clean-theme/docs/getting-started/upgrading-to-v1/) for more information.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/chrisrhymes/bulma-clean-theme. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is set up just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

