# Spree WYSIWYG

This extension adds a WYSIWYG editor (<a href="http://www.wymeditor.org/">WYMeditor</a>) to the products description textarea.

<p align="center">
  <img src="https://raw.github.com/norekinc/spree_wysiwyg/2-3-stable/screenshots/screenshot.png" alt="spree_wysiwyg screenshot" title="spree_wysiwyg screenshot" width="721" height="449" />
</p>

## Installation

Add this line to your application's Gemfile:

    gem 'spree_wysiwyg'

Or add this line to your application's Gemfile:

    gem 'spree_wysiwyg', :git => 'https://github.com/fernandoaleman/spree_wysiwyg', :branch => '2-3-stable'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install spree_wysiwyg

## Usage

Once installed, run:

    rails generate spree_wysiwyg:install

Or you may need to run:

    bundle exec rails generate spree_wysiwyg:install

### Internationalization / i18n

Use <a href="https://github.com/spree/spree_i18n">spree_i18n</a> for translations.


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

Copyright (c) 2013 spree_wysiwyg, released under the New BSD License
