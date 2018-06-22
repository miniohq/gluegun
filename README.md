# Gluegun
Gluegun glues markdown files to generate a beautiful documentation site.
 
## Pre-Requisite

- ruby2.4 or above (download https://rvm.io/ and use rvm to manage your ruby)
- yarn 1.7.0 (download from https://yarnpkg.com)

## Installation
Add this line to your application's Gemfile:

```ruby
gem 'gluegun'
```

And then execute:

```
rake
```

Or install it yourself as:

```
gem install gluegun
```

Or in your script:

```ruby
    require `gluegun`
```
    
## Usage

```
        NAME:
          gluegun - Glues github markdown files to a documentation site.

        USAGE:
          gluegun COMMAND [ARGUMENTS...]

        COMMANDS:
          generate Generate new docs site with an URL or file path.
```

## Example

```
gluegun generate site.yml
```

## Building Gluegun Gem
Build the gem using the command 

```
gem build gluegun.gemspec
```

Install the gem
```
gem install gluegun
```

Run the gluegun CLI 
```
gluegun generate ./site.yml
````
