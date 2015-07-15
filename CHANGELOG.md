# Changelog

## 1.6.0 (July, 15, 2015)

This is the last version that uses the API V1.

Since the migration from V1 to V2 has no breaking changes probably you are good to upgrade to 2.x. Otherwise lock the gem to 1.x in your `Gemfile`: `gem "filepicker-rails", "~> 1.0"`

More info about the migration [here](https://www.filepicker.com/documentation/file_ingestion/javascript_api/migration?v=v2).

### features

- The latest gem 1.x stays with API V1
- Revert the changes of 1.5.0 and 1.5.1 and re-release 1.4.0 as 1.6.0

## 1.5.1 (July, 8, 2015)

### bug fixes

- Update `filepicker_image_url` to merge query params into current url params if they exist

## 1.5.0 (June, 10, 2015)

### features

- Update `filepicker_js_include_tag` to use the V2 api

### improvements

- Declare FilepickerRails::Tag as a private module

## 1.4.0 (May, 7, 2015)

### features

- Add option for max number of files
- Add store_container option to filepicker_field
- Add open_to option to filepicker_field
- Add filepicker_field_tag helper method

### improvements

- Move from end-of-life multi_json to json

## 1.3.0 (December 31, 2014)

### features

- Adds filepicker_save_link

### improvements

- Adds support to Rails 4.2

## 1.2.0 (August 23, 2014)

### features

- filepicker_image_tag now works with policies

### improvements

- update to RSpec 3

### bug fixes

- Do not modify original url when using cdn

## 1.1.0 (March 30, 2014)

### features

- Add option to use a CDN
- Add option for max file size
- Add option to rotate image

### improvements

- Running specs on rails 3.2.x and 4.0
- Only append convert? when is needed

### misc

- Add license to gemspec
- Improved README with a bit more documentation for onchange callback

## 1.0.0 (September 20, 2013)

### features

### improvements

- Moved to a rails engine
- Add specs <3
- Add to Travis CI
- Create CHANGELOG
- Create CONTRIBUTING
- Add versioning, issue, contributing and credits sections on README
- Add rubygems badge
- Add codeclimate badge
- Add coveralls badge

### bug fixes

- Support rails 4

## Previous

The changelog began with version 1.0.0 so any changes prior to that
can be seen by checking the tagged releases and reading git commit
messages.
