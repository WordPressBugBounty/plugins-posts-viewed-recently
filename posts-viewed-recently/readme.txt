=== Posts Viewed Recently ===
Contributors: amitaits, kka284556
Donate link: https://www.paypal.me/astx
Tags: recent, recently, last, viewed, visited, post, posts, page, pages, widget, thumbnail, thumbnails, sidebar, plugin, wordpress, custom, taxonomy
Requires at least: 3.0
Tested up to: 5.6
Stable tag: 1.3.2
License: GPLv2 or later

Posts Viewed Recently plugin shows recently viewed posts or pages by a visitor as a responsive sidebar widget or on a page/post using the shortcode.

== Description ==

This plugin contains a responsive widget for showing posts or pages recently visited by a visitor. Posts Viewed Recently plugin is capable to show custom post types and you can also show this widget on your page/post using shortcode provided in widget options.

With this plugin you can choose post types to show, the number of posts to display, show or hide the featured image, dimensions of the featured image and alternate image URL if featured image is not available, and display post date or not. 

For more detail, visit [the plugin page](https://www.astech.solutions/wordpress-javascript-jquery-plugins/posts-viewed-recently/) at our official website. You are welcome to post issues, contribution and feature requests at [GitHub repo](https://github.com/as-tx/posts-viewed-recently).

To show this widget in any post/page, copy and paste the shortcode generated by the widget to that post or page. 

<strong>This plugin uses cookie and if cookies are not accepted or any two single posts (of selected post types) haven't been clicked yet, no output will be displayed.</strong>

Since Posts Viewed Recently plugin uses cookies so it is your responsibility to obtain user consent before using the plugin to comply with GDPR. Generally, your  GDPR related WordPress plugin/implementation should be able to delete cookies upon rejection by the user. In such case, the plugin won't output anything.


== Installation ==

This section describes how to install the plugin and get it working.

e.g.

1. Install Posts Viewed Recently plugin either via the WordPress.org plugin directory or by uploading the posts_viewed_recently folder to `/wp-content/plugins/` directory at your server
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Drag Posts Viewed Recently widget from list of your `Available Widget` to the sidebar where you want to place the widget
4. Customize the setting as per your requirement and you're ready


== Frequently Asked Questions ==

= How to use it? =
Enable the plugin and place the widget in the sidebar wherever you want

= What if some of my posts/pages have no featured image attached? =
You can specify an alternate image URL in the widget option. Image from that URL will be used if no featured image found

= How can I show this widget into my post or page? =
Use shortcode generated by the widget to display into your page/post

= Is this responsive? =
Yes, widget created by Posts Viewed Recently plugin is responsive

= Does this plugin has its own CSS rule for link and text colours? =
No, this plugin doesn't have any CSS rule for link and text colours. It just inherits those from your theme's styles


== Screenshots ==
1. Widget options
2. Viewing the widget with thumbnail


== Changelog ==

= 1.3.2 =
* Bugfix: Missing closing tags when the number of posts viewed was more than the number of posts to show. Issue fixed

= 1.3.1 =
* Direct file access blocked
* Code optimization by avoiding arguments parsing till the cookie existence check

= 1.3 =
* Security bug fixes and code enhancement

= 1.2 =
* Plugin updated to show post date in the format as set in WordPress setting

= 1.1 =
* Bugfix: The widget in the sidebar and the current post, both were displaying the same publish date. Issue fixed

= 1.0 =
* Let you specify a title, post types to select, set number of posts, enable/disable featured image, its size and alternative image URL, display or not post date


== Upgrade Notice ==

= 1.3.2 =
* Bugfix: Broken HTML fixed

= 1.3.1 =
* Direct file access blocked
* Code optimization

= 1.3 =
Bugfix: Major security updates
Fixed: Depreciated constructor warning in PHP 7
Removed: PHP serialize/unserialize
Added: JSON encode/decode
Changed: Cookie name

= 1.2 =
Update: Post date format is the same as given in WordPress setting

= 1.1 =
Bugfix: Post date issue fixed

= 1.0 =
Initial release