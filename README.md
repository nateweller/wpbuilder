# wpbuilder
CLI executable for automated custom WordPress installation.

## Installation
1. Download `wpbuilder` and move the file to `~/bin`. You may need to create this directory.
2. Add the following to the bottom of your `.bash_profile` to include:
```
export PATH=$PATH:~/bin
```
3. Give `wpbuilder` executable permissions:
```
chmod +x ~/bin/wpbuilder
```
4. Edit the Config section of `wpbuilder` (lines 4-13) with your info.
5. Restart your CLI and run `wpbuilder` to get started!

## What the heck is this thing
`wpbuilder` is a command line tool for automating local WordPress installs, from downloading the latest version to initializing a database and installing some pre-set plugins.

#### Plugins
* Advanced Custom Fields Pro
* Better WP Security
* Custom Post Type UI
* Timber
