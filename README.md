Paytrail payments for Spree Commerce
====================================

Unofficial Paytrail payments for Spree Commerce. Doesn't use Connect API.

Should *NOT* be used in production, yet.

Installation
------------

Add spree_paytrail to your Gemfile:

```ruby
gem 'spree_paytrail'
```

Bundle your dependencies and run the installation generator:

```shell
bundle
bundle exec rails g spree_paytrail:install
```

Testing
-------

Be sure to bundle your dependencies and then create a dummy test app for the specs to run against.

```shell
bundle
bundle exec rake test_app
bundle exec rspec spec
```

When testing your applications integration with this extension you may use it's factories.
Simply add this require statement to your spec_helper:

```ruby
require 'spree_paytrail/factories'
```

Copyright (c) 2014 Ilkka Sopanen, released under the New BSD License
