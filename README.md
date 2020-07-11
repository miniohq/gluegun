<p align="center">
<img src="https://github.com/minio/gluegun/blob/master/lib/img/Gluegun_icon_1024px.png" width="140px">
</p>

# Gluegun
Gluegun glues markdown files to generate a beautiful documentation site.

## Prerequisite

A minimum version of ruby2.4 and node versions [6.x, 8.x, 9.x, 10.x] are supported.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'gluegun'
```

And then execute:

```
npm install
npm run compile
bundle
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
./gluegun generate https://github.com/gluegun/site.yml
```

Run the gluegun CLI

```
./gluegun generate ./site.yml
````
