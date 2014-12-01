# Ruby kata starter project

A really simple starting point for doing code katas in Ruby, using RSpec.

## Getting started

1. Download the project, or clone it using git
2. Install [bundler](http://bundler.io/) if necessary: `gem install bundler`
3. Run `bundle install --binstubs`
4. Run specs using `bundle exec rspec` or `bin/rspec`

A dummy spec and class are provided in `spec` and `lib` respectively &ndash;
delete these and replace with your own.

## Notes

If you're using [rvm](http://rvm.io/) and want to use a specific gemset, run
`rvm --rvmrc --create <ruby-version>@<gemset-name>` before step 2 above.

If you're using [direnv](https://github.com/zimbatm/direnv), there's a `.envrc`
file in the project to add `bin` to your path, so you can just run `rspec`.
