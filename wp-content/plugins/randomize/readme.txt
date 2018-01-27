=== Randomize ===
Contributors: se-schwarz
Tags: widget, plugin, sidebar, random, text, quotes, rotate, rotation, images, pictures
Requires at least: 4.3
Tested up to: 4.7.2
Stable tag: 1.3

Store and display randomized/rotated text by category in sidebar widget or templates.

== Description ==

Randomize simply displays randomized text. You're able to deposit text passages and quotes in the administration back-end by categories. You can use the widget, a shortcode or template tag to show up randomized text on your site.

= Notice! =

I am not the author of this plugin. The original author has discontinued the development, so that I decided to continue the free distribution under the new name “Randomize”. It's based on "Random Text" by pantsonhead.

To continue the development of this plugin I may need your help! So if you have skills, mail to me.

== Installation ==

1. Upload the zip to your WordPress installation and activate it.
2. Switch to "Appearance" -> "Widgets" for using the widget OR embed a shortcode/template tag.
3. Manage your entries in "Settings" -> "Randomize".

Note: During installation, Randomize creates a new table to your WP database to store the entries by category. After setup you should see two sample entries.
By uninstalling the plugin the DB tables will be removed also.

== Screenshots ==

1. Placing the widget with it's options
2. Randomize settings overview
3. Adding more records to Randomize using bulk import
4. output on the site

== Frequently Asked Questions ==

= Can I use shortcodes? =

Yes, you can use [randomize] or [randomize category="EXAMPLE_CATEGORY"] or even [randomize category="EXAMPLE_CATEGORY" random="1"].

= What about template tags? = 

You can use something like this, where 'EXAMPLE_CATEGORY' is the group you wish to select items from:

< ?php randomize('EXAMPLE_CATEGORY'); ?>

Replace EXAMPLE_CATEGORY with one of your previous created categories.

= Can I embed images? = 

You are able to embed images by using the general HTML <img> tag. Maybe you would like to create an own category for images in Randomize.

== Changelog ==

= v1.3 2017-03-05 =

* Hotfix

= v1.1 2016-10-20 =

* Replaced function "WP_Widget()" with "parent::__construct()", which is deprecated since version 4.3.0 of WordPress

= v1.0 2014-06-03 =

* Initial release
