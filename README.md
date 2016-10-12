# Minimal Jekyll Theme

![Minimal Jekyll Theme Screenshot](http://i.imgur.com/FH7mlHH.jpg)

:boom: **This theme is a work in progress.** :boom:

- Theme uses [Tachyons Css](http://tachyons.io)
- Theme works with > Jekyll 3.3

## Installation

1. Install Jekyll:

		gem install jekyll bundler

2. Add the following lines to your Jekyll site’s Gemfile:  


		# Theme
		gem "minimal-jekyll-theme"

		# Plugins
		group :jekyll_plugins do
		  gem 'jekyll-feed'
		  gem 'jekyll-sitemap'
		  gem 'jekyll-seo-tag'
		  gem 'jekyll-admin'
		end


3. Add this line to your Jekyll site’s config.yml file:


		theme: minimal-jekyll-theme


4. Create a css/minimal.scss file that includes:


		---
		---

		@import "minimal";


5. And then run Bundler:

		bundle install


6. To view your new theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`.

## Usage
### Archive Page
Copy `writings.html` page from `example` folder in to your site root directory.

### Categories & Tags Pages
Copy `categories.html` page and `tags.html` from `example` folder in to your site root directory.

### Author Image
Add your `author.jpg` image in `images` folder.

### navigation
Create `_data` folder and add `navigation.yml` file found in `example` folder.

## Contributing

Bug reports and pull requests are welcome on GitHub at [https://github.com/desiredpersona/minimal-jekyll-theme](https://github.com/desiredpersona/minimal-jekyll-theme). This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
