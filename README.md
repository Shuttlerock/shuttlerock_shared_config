# ShuttlerockSharedConfig

Update shared config (.rubocop.yml, .codeclimate.yml, .eslintrc, .stylelintrc)
for Shuttlerock's projects.

## Installation in Ruby application

Add this line to your application's Gemfile:

```ruby
gem 'shuttlerock_shared_config'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install shuttlerock_shared_config

## Usage in Ruby application

    $ rake shuttlerock_shared_config:update_codeclimate  # Update .codeclimate.yml
    $ rake shuttlerock_shared_config:update_eslint       # Update .eslint.yml
    $ rake shuttlerock_shared_config:update_rubocop      # Update .rubocop.yml
    $ rake shuttlerock_shared_config:update_stylelintrc  # Update .stylelintrc
    $ rake shuttlerock_shared_config:update              # Update all

## Installation in JS application
    $ npm install shuttlerock_shared_config

Add ' "update_eslintrc": "npx update_eslintrc" ' to yours package.json:

```
scripts: {
...
"update_eslintrc": "npx update_eslintrc"
...
}
```
## Usage in JS application

    $ npm run-script update_eslintrc
    or
    $ yarn run update_eslintrc

## How to Update a NPM Package

When you make changes, you can update the package using:
```
$ npm version <update_type>
```

Where <update_type> is one of the semantic versioning release types, patch, minor, or major.
This command will change the version number in package.json.
Note: this will also add a tag with the updated release number to your git repository if you have linked one to your npm account.
After updating the version number run:

```
$ npm publish
```
You can get more information [here](https://docs.npmjs.com/getting-started/publishing-npm-packages).

## How to Add npm-owner to NPM Package

You can read about this [here](https://docs.npmjs.com/cli/owner).

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the ShuttlerockSharedConfig project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/shuttlerock_shared_config/blob/master/CODE_OF_CONDUCT.md).
