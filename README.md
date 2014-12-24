# Rellyfish

A ruby gem wrapper for cjellyfish: https://github.com/sunlightlabs/jellyfish , for doing approximate and phonetic matching of strings.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'rellyfish'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install rellyfish

## Usage

```ruby
require 'rellyfish'

include Rellyfish

levenshtein_distance('jellyfish', 'smellyfish')
jaro_distance('jellyfish', 'smellyfish')
metaphone('Jellyfish')

```

## Contributing

1. Fork it ( https://github.com/[my-github-username]/rellyfish/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
