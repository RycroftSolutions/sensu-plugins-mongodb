## Sensu-Plugins-mongodb

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-mongodb.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-mongodb)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-mongodb.svg)](http://badge.fury.io/rb/sensu-plugins-mongodb)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-mongodb/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-mongodb)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-mongodb/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-mongodb)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-mongodb.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-mongodb)
[ ![Codeship Status for sensu-plugins/sensu-plugins-mongodb](https://codeship.com/projects/fb6c0ce0-dc03-0132-9f1d-025863fcc952/status?branch=master)](https://codeship.com/projects/79855)

## Functionality

## Files
 * bin/check-mongodb.py
 * bin/metrics-mongodb.rb

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-mongodb -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-mongodb`

#### Bundler

Add *sensu-plugins-mongodb* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-mongodb' do
  options('--prerelease')
  version '0.0.1.alpha.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-mongodb' do
  options('--prerelease')
  version '0.0.1.alpha.1'
end
```

## Notes
