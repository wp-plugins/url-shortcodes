=== URL ShortCodes ===
Contributors: cgarvey
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6137112
Tags: cgarvey, short code, shortcode, template, stylesheet, url
Requires at least: 2.9.0
Tested up to: 2.9.2
Stable tag: rel_1-00

URL ShortCodes plugin adds support for a basic short codes to use in your post/page editor that produce correct absolute URLs.

== Description ==
Sometimes you want to put the base URL (that of the blog, or that of the active template) in your content editor. Times when the template customising isn't quite flexible enough.
With this plugin you can use [url_base] to output the base URL of the blog (as set in your Settings). Or, you can use [url_template] to output the URL of the active template.

For example `<img src="[url_base]/test.png />` in your editor might output `<img src="http://localhost/wordpress/test.png" />` (if http://localhost/wordpress is what you have configured as your blog URL in Settings).

The supported short codes are as follows:
* [url_base] - the configured blog URL (set in Settings). E.g. http://localhost/wordpress
* [url_template] - the URL of the active template. E.g. http://localhost/wordpress/wp-content/themes/mytheme1

== Changelog ==
* Version 1.00 - Initial release.

== Installation ==

There are 2 ways of installation. If your setup supports it, you can search for the plugin, by name, within your WordPress control panel and install it from there.
Alternatively, you download the .zip file, unzip it, and copy the resultant `url_short_codes` folder to the `wp-content/plugins/` folder of your WordPress instaltion folder.

== Frequently Asked Questions ==
There are no FAQs at this time. Feel free to suggest some!

== Screenshots ==

1. Sample short code use.
2. Rendered output.

== License ==
This plugin uses the GPLv3 license.

