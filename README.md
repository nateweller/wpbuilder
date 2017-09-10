# wpbuilder
CLI executable for automated custom WordPress installs on macOS.

## Requirements
#### wp-cli
`wpbuilder` requires `wp-cli`:
```
$ curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar
$ chmod +x wp-cli.phar
$ sudo mv wp-cli.phar /usr/local/bin/wp
```
#### .bash_profile PATH
If you do not have a place on your machine for this kind of thing:
```
mkdir '~/bin'
```
and add the following to the bottom of your `.bash_profile` to include:
```
$ export PATH=$PATH:~/bin
```
## Installation
1. Download `wpbuilder` and move the file to `~/bin`.
2. Give `wpbuilder` executable permissions:
```
$ chmod +x ~/bin/wpbuilder
```
3. Edit the Config section of `wpbuilder` (lines 4-13) with your info.
4. Restart your CLI and run `wpbuilder` to get started!

## What's in the Box
* Advanced Custom Fields Pro
* Better WP Security
* Custom Post Type UI
* Timber
