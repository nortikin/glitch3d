# Glitch3d

By altering .obj file data you can get something like this :
<img style="width:50%;height:50%;display:block;margin: 0 auto;" src="https://raw.githubusercontent.com/pskl/glitch3d/master/fixtures/demo.png">

## Disclaimer
Work in progress

Usage
---
- `3dglitch source_file_name` (a .obj file)
- then render the generated `source_file_name_glitched.obj` file with your favorite rendering tool (Photshop, Blender)

## A quick note on the .obj file format

- v -> represents a vertice position
- f -> represents a face (contains references to vertices, can be triangle, quad...)
- vt -> texture UV map
- vn -> vertex normal

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

TODO: Write usage instructions here

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/glitch3d. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
