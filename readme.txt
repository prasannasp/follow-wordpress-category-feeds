=== Follow WordPress Category Feeds ===
Contributors: prasannasp
Donate link: http://www.prasannasp.net/donate
Tags: categories, RSS, feed, link, follow, subscribe, post, category
Requires at least: 3.1
Tested up to: 3.5.1
Stable tag: 2.1.3
License: GPLv2 or later
License URI: http://www.gnu.org/copyleft/gpl.html

This plugin adds link for the category feeds after post content.

== Description ==

Just like the normal Wordpress site feed, wordpress categories and tags also has feeds. The category feed is located at `site.url/category/categoryname/feed`. This plugin automatically adds the RSS feed link to the current post categories after the post content. By default the plugin shows category feed link on single posts. You can change it's settings to show it on other pages, such as archives as well. You can change it's title in WP-Admin --> Settings --> Follow Category Feeds.

Visit [this page](http://www.prasannasp.net/wordpress-plugins/) for more **WordPress Plugins** from the developer.

Visit [developer's blog](http://www.prasannasp.net/) for more information on WordPress and plugins.

== Installation ==

1. Extract the contents of the .zip archive

2. Upload the `follow-category-feeds` folder to your `wp-content/plugins` directory.
     
3. Activate the plugin through the 'Plugins' menu in WordPress.

== Screenshots ==

1. Plugin showing link to RSS feed for Linux, Open Source and Ubuntu categories in post footer
2. Plugin Options Page

== Changelog ==

= 2.1.3 =

* Added option to include `rel="nofollow"` in links.

= 2.1.2 =

* Code enhancement. The options stored in the database will be retained even after deactivating the plugin. This is to prevent the removal of plugin options upon plugin update/reactivation. If you want to clear the database entries upon plugin deactivation, select <strong>Restore defaults upon plugin deactivation/reactivation</strong> in plugin options.

* Added link to support forum.

= 2.1.1 =

* Fixed the issue of the category feed function being called on pages, which doesn't belong to any category.

= 2.1 =

* Added option to show the category feed link on other pages, such as home page and archives

* Added `follow-cat-feed` class to the category links. You can use `.follow-cat-feed` CSS class to style it.

= 2.0 =

* Fixed the bug in using `get_category_feed_link` function, which was causing category feed links to strip off `/feed` in URL. 

* Added option to change the category feed link title. You can change this in WP-Admin --> Settings --> Follow Category Feeds.

= 1.1 =
* Since `get_category_rss_link` function is deprecated, we are using `get_category_feed_link` function to get category feed link.

* Added `fcfeeds` class to the output. So, you can style it now using `.fcfeeds` class.

= 1.0 =

* Initial public release

== Upgrade Notice ==
