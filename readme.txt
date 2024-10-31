=== Optimizer Shortcodes - Business Name ===
Contributors: businessoptimizer, rajivlodhia
Tags: business name, company name, name shortcode, optimizer shortcodes, business optimizer
Requires at least: 4.7
Tested up to: 6.0
Requires PHP: 7.3
Stable tag: 1.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

A very simple plugin that turns your company/business name into a shortcode. This plugin provides a field and shortcode for your business name allowing you to use it anywhere on your site. If you ever need to update your business name, you'd just need to change it in one place.

This plugin works together with other Optimizer Shortcodes plugins. Find a list of all our Optimizer Shortcodes plugins [here](https://businessoptimizer.org/collections/plugins).

== Installation ==

1. Copy the `optimizer-shortcodes-business-name` folder into your `wp-content/plugins` folder
2. Activate the Optimizer Shortcodes - Business Name plugin via the plugins admin page
3. Set your business name in the new field (`/wp-admin/admin.php?page=optimizer-shortcodes`)

== Usage Instructions ==

After setting your business name in the new settings page (`/wp-admin/admin.php?page=optimizer-shortcodes`), you can use the shortcode [optimizer_business_name] anywhere on your site to display your business name.
If you need to use the field value in your theme files or template, you can print it with PHP like this:
<?php echo do_shortcode('[optimizer_business_name]'); ?>

== Credits ==

Plugin built by [Rajiv Lodhia](https://rajivlodhia.com/) for [Business Optimizer](https://businessoptimizer.org/)

== Screenshots ==
1. The new menu page and custom business name field

== Changelog ==

= 1.0.0 =
* Initial Release.
