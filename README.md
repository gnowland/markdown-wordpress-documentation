# Markdown WordPress Docs
A lightweight WordPress Plugin that generates documentation pages for your WordPress site from Markdown files.

## Use

1. Add Markdown files to `docs/`
2. [Install](#install) & Activate plugin in WordPress Admin

### Details

- `/docs` should contain all your Markdown files
- Links to `../[DOCUMENT_NAME.md]`, `./[DOCUMENT_NAME.md]` or `docs/[DOCUMENT_NAME.md]` will automatically route to display the file using URL Parameters `?page=docs&doc=[DOCUMENT_NAME].md`
  - I recommend dividing files into subjects and including a Table of Contents in `docs/README.md`.
- The help page will be displayed in the Dashboard sub-menu

## Installation ##

### Composer ###

```shell
composer require gnowland/markdown-wordpress-documentation
```

Activate with [wp-cli](http://wp-cli.org/)

```shell
wp plugin activate markdown-wordpress-documentation
```
or in the WordPress Admin panel.

### Git ###

* `git clone` into your sites plugin folder
* Activate via WordPress or wp-cli (see above) or in WordPress Admin

### Manually ###

* Download the [zip file](https://github.com/gnowland/wp-jet-fuel/archive/master.zip)
* Unzip to your sites plugin folder
* Activate via WordPress Admin or wp-cli (see above)
