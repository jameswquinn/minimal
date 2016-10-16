# Minimal Jekyll Theme

![Minimal Jekyll Theme Screenshot](/screenshot.jpg)

:boom: **This theme is a work in progress.** :boom:


## Features

- Compatible with Jekyll 3.3.x and GitHub Pages
- Support for Jekyll's built-in Sass/SCSS preprocessor
- Several layout options (single, archive, landing pages)
- SEO optimized using Jekyll-seo-tag
- Optional comments ([Disqus](https://disqus.com/),
- Optional analytics ([Google Analytics](https://www.google.com/analytics/) and custom).
- System-fonts


## Installation

1. Install Jekyll:

		gem install jekyll bundler

2. Add the following lines to your Jekyll site’s Gemfile:  


		source "https://rubygems.org"

		# Jekyll
		gem "jekyll"

		# Theme
		gem "minimal-jekyll-theme"

		# Plugins
		group :jekyll_plugins do
			gem 'jekyll-feed'
			gem 'jekyll-sitemap'
			gem 'jekyll-seo-tag'
			gem 'jekyll-admin'
			gem 'jemoji'
		end


3. Add this line to your Jekyll site’s config.yml file:


		theme: minimal-jekyll-theme


4. And then run Bundler:

		bundle install


5. To view your new theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`.


## Usage

The example folder contains a working demo of this theme.

### Archive Page
Copy `writings.html` page from `example` folder in to your sites root directory.

### Categories & Tags Pages
Copy `categories.html` page and `tags.html` from `example` folder in to your sites root directory.

### Author Image
Create `assets/images` folder in your sites root directory and add your `author.jpg` image.

### Navigation
Create `_data` folder in your sites root directory and add `navigation.yml` file found in `example` folder.


## Credits

### Creator

**Desired Persona**

- <https://desiredpersona.com>
- <https://twitter.com/desiredpersona>
- <https://github.com/desiredpersona>

### Other:

- [Jekyll](http://jekyllrb.com/)
- [Tachyons](http://tachyons.io)

## Contributing

Bug reports and pull requests are welcome on GitHub at [https://github.com/desiredpersona/minimal-jekyll-theme](https://github.com/desiredpersona/minimal-jekyll-theme). This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
