# jekyll-theme-poor

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-theme-poor"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-theme-poor
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-theme-poor

## Usage

First, you need to give some information about yourself in `_config.yml`.

```yml
email:
github_username:
title:
description:
author:
```

`mathjax` is enabled by default, you can turn off this by adding settings below.

```
mathjax:
  enable: false
```

You can alse write your own `sidebar.html` and `footer.html` and put them in `_includes`.

## Preview

Full preview in [https://kemingy.github.io/jekyll-theme-poor/](https://kemingy.github.io/jekyll-theme-poor/)

### Desktop

![Desktop](/assets/img/desktop.png)

### Phone

![Phone](/assets/img/phone.jpg)

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/momingcoder/jekyll-theme-poor. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `jekyll-theme-poor.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

