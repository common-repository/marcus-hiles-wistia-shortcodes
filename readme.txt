=== Marcus Hiles Wistia Shortcodes ===
Contributors: marcushiles
Donate link: https://marcus-hiles.com/
Tags: wistia, Gutenberg, blocks, block
Requires at least: 4.6
Tested up to: 5.0
Stable tag: 4.0
Requires PHP: 5.6
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Easily embed Wistia videos using a shortcode or with a Wistia video Gutenberg block.

== Description ==

This plugin simplifies adding Wistia videos to your site. You can use a shortcode or insert a video with a custom Gutenberg block.  

You won't have to deal with the large embed codes which load the javascript in the middle of the page. The main Wistia javascript file will only be loaded once per page, and associated JSON files will be grouped together in the footer.

== Installation ==

Install the plugin

1. Upload the plugin files to the `/wp-content/plugins/plugin-name` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress

There are no settings. To use, [mh_wistia_embed id="<wistia_id>"] or use the MH: Wistia Video block.

Get the wistia ID from the embed code or the url of the video in wistia.
= Shortcode Options =
**id**: the wistia ID for the video. Required.
**embed_type**: inline or popover. Defaults to inline.
**animatethumbnail**: Whether to animate the hover effects on the thumbnail. Default is false
**responsive**: Use responsive video. Default is false
**height**: IF not responsive, use height
**width**: IF not responsive, use width
**player**: js or iframe. Defaults to js


== Changelog ==

= 1.3 =
* Check for if Gutenberg exists

= 1.2 =
* Fix missing file

= 1.1 =
* Add Gutenberg Support
* Gutenberg block for video

= 1.0 =
* Initial release