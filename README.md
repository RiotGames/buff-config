# Buff::Config

[![Gem Version](https://badge.fury.io/rb/buff-config.svg)](http://badge.fury.io/rb/buff-config) [![Build Status](https://travis-ci.org/berkshelf/buff-config.svg?branch=master)](https://travis-ci.org/berkshelf/buff-config)

A simple configuration class

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'buff-config'
```

And then execute:

```sh
$ bundle
```

Or install it yourself as:

```sh
$ gem install buff-config
```

## Usage

```ruby
require 'buff/config/json'

class MyConfig < Buff::Config::JSON
  attribute 'chef.chef_server_url'
end

my_config = MyConfig.new
my_config.chef.chef_server_url #=> nil
```

# Authors and Contributors

- Jamie Winsor ([jamie@vialstudios.com](mailto:jamie@vialstudios.com))
- Kyle Allan ([kallan@riotgames.com](mailto:kallan@riotgames.com))

Thank you to all of our [Contributors](https://github.com/berkshelf/buff-config/graphs/contributors), testers, and users.
