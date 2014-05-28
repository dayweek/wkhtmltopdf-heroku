# wkhtmltopdf-heroku

This is fork of [apancik's wkhtmltopdf-heroku](https://github.com/apancik/wkhtmltopdf-heroku)

This gem uses wkhtmltopdf version 0.12.1-rc and configures wicked_pdf to use this binary.

Two binaries are there:

`wkhtmltopdf-amd64` for Heroku, version `0.12.1-c22928d`

`wkhtmltopdf-i368` for OS X, version `0.12.1-7fac78c`

It worked on OS X and Heroku for me.

## Installation

Add this line to your application's Gemfile:

    gem 'wkhtmltopdf-heroku', git: 'https://github.com/dayweek/wkhtmltopdf-heroku.git'

And then execute:

    $ bundle install

## Contributing

1. Fork it ( http://github.com/apancik/wkhtmltopdf-heroku/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
