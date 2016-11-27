# Emojione::Rails [![Gem Version](https://badge.fury.io/rb/emojione-rails.png)](http://badge.fury.io/rb/emojione-rails)

Sprocket/Rails emojione package, see http://emojione.com

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'emojione-rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install emojione-rails

## Sync images

Images can be copied to your public directory with `rake emojione` in your app. This is the recommended approach since the images will be available at a consistent location and not slow down your asset pipeline.

```
$ rake emojione
```

## Usage

In your JavaScript manifest (e.g. `application.js`):

    //= require emojione

In your CSS/SCSS manifest (e.g. `application.scss`):

    @import "emojione";

If you want to use [Emojione Awesome](https://github.com/Ranks/emojione/tree/master/lib/emojione-awesome), you can also optionally add the following line to your CSS/SCSS manifest:

    @import "emojione-awesome";

## Documentation

Everything is available at https://github.com/Ranks/emojione

## Gotcha

This gem bundle emojione png and svg version but not the sprites (for size purposes mainly). If you need to use the emojione sprites, this gem is not for you.

## Licensing

See [LICENCE](https://github.com/dimelo/emojione-rails) file

## Contributing

1. Fork it ( https://github.com/dimelo/emojione-rails/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
