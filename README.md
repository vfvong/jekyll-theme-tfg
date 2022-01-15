# Jekyll Theme TFG

TFG is a tiny friendly giant Jekyll theme for powering blogs. The name of this theme is from [Koenigsegg Gemera](https://www.koenigsegg.com/gemera/)'s engine ["Tiny Friendly Giant"](https://www.koenigsegg.com/gemera/tiny-friendly-giant-engine/). It is small when it comes to emissions and consumption, and at the same time, it is big when it comes to power, torque, and sound. The target of this theme is similar—While providing friendly and powerful blog functions, try to keep the code and the design as tiny as possible.

## Highlight Features

- Light and dark mode, via [`prefers-color-scheme`](https://web.dev/prefers-color-scheme/)
- [Google Analytics 4](https://analytics.google.com/analytics/web/)
- [Disqus](https://disqus.com/)
- [MathJax](https://www.mathjax.org/)
- [Font Awesome](https://fontawesome.com/)

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-theme-tfg"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-theme-tfg
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-theme-tfg

If your website is hosted on GitHub Pages, you can install this theme via [`jekyll-remote-theme`](https://github.com/benbalter/jekyll-remote-theme).

Add the following to your `Gemfile`:

```ruby
gem "jekyll-remote-theme"
```

And add this line to your Jekyll site's `_config.yml`:

```yml
plugins:
  - jekyll-remote-theme
```

Add the following to your site's `_config.yml`:

```yml
remote_theme: vfvong/jekyll-theme-tfg
```

## Usage

Ease of use is one of the design goals of TFG. Basically, you only need to refer to the [`_config.yml`](https://github.com/vfvong/jekyll-theme-tfg/blob/gh-pages/_config.yml) file of the demo to set the basic parameters required to run the website.

### Customization

You can of course fork the entire repository and make custom changes on your copy, but there is a much cleaner way: after referencing the theme, you just need to copy the [`_sass/tfg/_variables.scss`](https://github.com/vfvong/jekyll-theme-tfg/blob/main/_sass/tfg/_variables.scss) file to your repository in the corresponding path, and then modify some variables, you can customize the color and fonts you like.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/vfvong/jekyll-theme-tfg. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `jekyll-theme-tfg.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
