# Minimal Jekyll Theme

![Minimal Jekyll Theme Screenshot](/screenshot.jpg)

:boom: **This theme is a work in progress.** :boom:

This Theme uses:
- [Tachyons Sass](https://github.com/tachyons-css/tachyons-sass) - Create fast loading, highly readable, and 100% responsive interfaces with as little css as possible with [Tachyons](http://tachyons.io).
- System-fonts
- Theme works with > Jekyll 3.3

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

## Contributing

Bug reports and pull requests are welcome on GitHub at [https://github.com/desiredpersona/minimal-jekyll-theme](https://github.com/desiredpersona/minimal-jekyll-theme). This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
