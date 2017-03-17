# Glitch3d

By altering .obj file data you can get something like this :

<img src="https://raw.githubusercontent.com/pskl/glitch3d/master/fixtures/demo.png" width="400">

This gem uses the Blender Python API to produces renders headlessly.

## Warning

Setting `BLENDER_EXECUTABLE_PATH` in your environment is required.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'glitch3d'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install glitch3d

## Usage

- `glitch3d file.obj`

Options:
- `mode` : (localized|default|none)
- `shots-number` : integer representing the number of - images desired
- `quality` : (high|low)

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/pskl/glitch3d. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

## TODO
- write specs
