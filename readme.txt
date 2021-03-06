=== Scalable Vector Graphics (SVG) ===
Contributors: sterlo
Donate link: http://sterlinghamilton.com/
Tags: svg, scalable vector graphics
Requires at least: 3.0
Tested up to: 3.3.1
Stable tag: trunk

SVG files are two-dimensional vector graphics, that can be both static and dynamic. This plugin allows your to easily use them on your site.

== Installation ==

1. Upload `scalable-vector-graphics.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Use SVG files just like you would use a normal image file.

== Changelog ==

= 1.0 =
* I N C E P T I O N
= 1.1 =
* Fixing a typo. This typo caused ONLY SVG files to be allowed to upload via the media uploader.
= 1.2 =
* One less required parameter and a graceful fail over to a valid implementation type. Props @Phil
= 2.0 =
* I broke everything. I'm sorry, but it had to be done.
* Basically how I had approached the problem before was wrong. It is now being done properly using the correct mime/type.
* Shortcodes are no longer needed, you can now use SVG files as you would any other image.
* Previews now show up in the media area for SVG files.
* IMPORTANT: Anyone using the version prior to 2.0 were using shortcodes to display SVG files. You will have to go back and replace those shortcodes with actual image tags. If you're not familiar with HTML, you can just delete the shortcode out of the page/post and then insert the SVG file as you would any other image.
* Thanks to the guys over at mozilla.org for kicking me in the butt to actually fix this thing: https://bugzilla.mozilla.org/show_bug.cgi?id=721830
