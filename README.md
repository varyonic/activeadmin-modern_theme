# ActiveAdmin::ModernTheme

See https://github.com/activeadmin/activeadmin/pull/3862

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'activeadmin-modern_theme'
```

And then execute:

    $ bundle

## Usage

active_admin.css.scss should contain:

```
@import "active_admin/modern/mixins/all";
@import "active_admin/modern/base";
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/activeadmin-modern_theme.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
