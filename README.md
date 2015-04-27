## Sensu-Plugins-kegbot

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-kegbot.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-kegbot)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-kegbot.svg)](http://badge.fury.io/rb/sensu-plugins-kegbot)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-kegbot/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-kegbot)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-kegbot/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-kegbot)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-kegbot.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-kegbot)

## Functionality

## Files
 * bin/check-kegbot.rb
 * bin/metrics-kegbot.rb

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-kegbot -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-kegbot`

#### Bundler

Add *sensu-plugins-sensu-plugins-kegbot* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-kegbot' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-kegbot' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
