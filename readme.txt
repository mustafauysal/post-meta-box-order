=== Post Meta Box Order ===
Contributors: m_uysl, wphandle
Tags: metabox,meta box,order,posts metabox,multisite
Requires at least: 3.0
Tested up to: 4.6
Stable tag: 2.0
License: GPLv2 (or later)

Easily change the order of the meta boxes on the posts screen.

== Description ==

This plugin help you to customize order of meta boxes on posts screen. It perfectly works with custom meta boxes.

= Usage =
 1. Install and activate plugin
 2. Order widgets via filters. This plugin hasn't interface for this.
 3. Update hash.


**If you want to force users** , `add_filter( 'post_meta_box_order_force_override', '__return_true' );`



== Installation ==

Extract the zip file and just drop the contents in the wp-content/plugins/ directory of your WordPress installation and then activate the Plugin from admin's Plugins page.
== Frequently Asked Questions ==

*   I changed meta boxes order but no effected users blog?
	-  Don't forget to change hash. You can use `post_meta_box_order_hash` filter for that.
*   Is it compatible with multisite?
	- Definitely!
*   How can prevent to users change order?
	-  Use filter: `add_filter( 'post_meta_box_order_force_override', '__return_true' );`



== Changelog ==

= 2.0 =
Filters added

= 1.0 =
Initial release


== Upgrade Notice ==

= 2.0 =

Please don't edit plugin source directly, you can use filters and be careful when upgrade to 2.0.
