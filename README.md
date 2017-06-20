# WordPress Base Plugin

## Description

This is a boilerplate WordPress plugin featuring namespace autoloading and integration with [Carbon Fields](https://github.com/htmlburger/carbon-fields). It is intended to be used as a starting point for creating quick WordPress plugins. It contains several examples and dependencies to get you started.

It may also be used as the means of [separating custom code](http://www.billerickson.net/core-functionality-plugin/) from the theme.

## Installation

### Clone Repository

1. At command prompt, change to your `wp-content/plugins` directory.
2. Close the repository: `git clone https://github.com/dmhendricks/wordpress-base-plugin.git`

### Composer

1. Clone a copy from from [GitHub](https://github.com/dmhendricks/wordpress-base-plugin)
2. Delete `/vendor` folder
3. Modify `composer.json` to suit your needs
4. Run `composer install` to install dependencies and autoload namespace

### Manual Installation

1. Download and extrtact ZIP archive from [GitHub](https://github.com/dmhendricks/https://github.com/dmhendricks/wordpress-base-plugin)
2. Upload to `wp-content/plugins/` folder
3. Activate through WP Admin > Plugins page.

## Change Log

#### 0.1.2

* Moved `/src` to `/app`

#### 0.1.1

* Refactored code
* Added `is_production()` and `is_ajax()` methods

#### 0.1.0 - December 26, 2016

* Initial commit

## Credits

Please support [humans.txt](http://humanstxt.org/). It's an initiative for knowing the people behind a web site. It's an unobtrusive text file that contains information about the different people who have contributed to building the web site.

**Carbon Fields:**

	URL: http://carbonfields.net/
	Author: htmlBurger.com
	Twitter: @htmlburger
	Author URI: https://htmlburger.com/
	Location: London, England

**PostTypes:**

	URL: https://github.com/jjgrainger/PostTypes/
	Author: Joe Grainger
	Twitter: @jjgrainger
	Author URI: https://jjgrainger.co.uk/
	Location: Falmouth, England
