# Movie Database

This is a custom Rails 5 exercise application used in my **Ruby on Rails trainings**. It implements a simple **movie database** with three resources:

- Movies (eg. "Star Wars")
- Actors (eg. "Harrison Ford")
- Roles, linking movies and actors together (eg. "Han Solo")

It is intended to be a base application to expand and experiment on, making use of Ruby on Rails' most important features and including some simple specs as a starting point.

### Getting started

1.  Install an up-to-date version of Ruby (2.5.x recommended.)
2.  Install Bundler: `gem install bundler`
3.  Clone this repository: `git clone https://github.com/manserei/moviedb.git`
4.  macOS only: install Homebrew dependencies via `brew bundle`.
5.  Execute the `bin/setup` script.

**Bonus step:** if you want the automatic poster fetching to work, you'll need to get a free API key for [omdbapi.com](http://www.omdbapi.com/) and provide it to the application by way of the `OMDB_API_KEY` environment variable.

If you plan on sharing the changes you're going to make to this application, please consider forking this repository into your own GitHub account.

### Recommended reading

- The [Ruby on Rails Guides](http://guides.rubyonrails.org/) are full of useful information on building Ruby on Rails apps. Use these extensively!
- The [Ruby on Rails API Reference](http://api.rubyonrails.org/) documents each and every class and method available in Ruby on Rails.
- The [JBuilder] gem is used to generate JSON responses.
- For tests, this app uses [RSpec] together with [FactoryBot] (also see its [GETTING_STARTED.md](https://github.com/thoughtbot/factory_girl/blob/master/GETTING_STARTED.md)) and [FFaker].
- [Capybara] is a framework for acceptance/feature/integration specs. This app uses it in conjunction with [Headless Chrome].

### Interested in training?

I offer Ruby on Rails training and consulting in Germany and across Europe. If you're interested in learning Rails or getting your development team up to speed, please don't hesitate to email me at hendrik@mans.de.

- _Hendrik Mans_

[jbuilder]: https://github.com/rails/jbuilder
[capybara]: https://github.com/teamcapybara/capybara
[headless chrome]: https://robots.thoughtbot.com/headless-feature-specs-with-chrome
[rspec]: http://rspec.info/
[factorybot]: https://github.com/thoughtbot/factory_girl
[ffaker]: https://github.com/ffaker/ffaker
