=== Icono - Pure CSS icons ===
Contributors: RavanH, Saeed Alipoor
Tags: icono, icon, icons, css icons
Requires at least: 2.6
Tested up to: 6.2
Stable tag: 1.5

Add Icono pure CSS icons to your WordPress site.

== Description ==

This lightweight plugin adds the [Icono pure css icons stylesheet](http://saeedalipoor.github.io/icono/) to your WordPress site.

= Icono =

Icono is a beautiful icon pack that needs no external resources except one small stylesheet. No javascript or font pack needed. Any tag can be made into an icon with **pure CSS** by giving it the appropriate class.
Just add an icono class to any type of element that supports the psuedo-element.

Icono was created and is maintained by [Saeed Alipoor](https://github.com/saeedalipoor) and currently features 130 pure CSS icons.

= Shortcode =

The shortcodes [icon name] and [icono name] are available for easy insertion of icons in post or text widget content. See http://saeedalipoor.github.io/icono/ for available icons and their corresponding name. You can simply paste the name (with or without "icono-") or use name="icono-name" as a parameter.

There are also the parameters scale, rotation, color and style (for custom styling) available.

= Example =

To show a big* red arrow pointing left:
`
[icon locationArrow scale=2 rotation=225 color=red]
`
* Note: scale=1 corresponds with the default of around 32 x 32 pixels for most icons.


== Installation ==

= Wordpress =

Quick installation: [Install now](http://coveredwebservices.com/wp-plugin-install/?plugin=icono-pure-css-icons) !

 &hellip; OR &hellip;

Go to that slick **Plugins > Add New** back-end page and search for "icono".

 &hellip; OR &hellip;

Follow these steps:

 1. Download archive.

 2. Upload the zip file via the Plugins > Add New > Upload page &hellip; OR &hellip; unpack and upload with your favourite FTP client to the /plugins/ folder.

 3. Activate the plugin on the Plug-ins page.

Done!

= Wordpress MU / WordPress 3+ in Multi Site mode =

Same as above but do a **Network Activate** to make the stylesheet and shortcode available on each site on your network. No database tables are created or manipulated and no activation hook needs to be run for it to function with default settings.


== Screenshots ==

1. See all 130 available icons and their names on http://saeedalipoor.github.io/icono/


== Upgrade Notice ==

= 1.5 =
Stylesheet update


== Changelog ==

= 1.4 =

Date: 15 Febuary 2019
Dev time: 1 hour

* Upgrade to stylesheet v1.5 from https://github.com/saeedalipoor/icono

= 1.4 =

Date: 23 July 2018
Dev time: 1 hour

* Upgrade to stylesheet v1.3.2
* Twenty Seventeen compatibility fix
* Older moz and webkit browser compatibility

= 1.0 =

Date: 22 March 2018
Dev time: 2 hours

* Latest stylesheet now included in plugin
* SSL compatible
* Switch to wp_add_inline_style

= 0.3 =

Date: 12 Jan 2015
Dev time: 4 hours

* Added shortcode parameters 'scale' and 'rotate'
* FIX: style patch for TwentyFifteen compat

= 0.2 =

Date: 11 Jan 2015
Dev time: 2 hours

* Added shortcodes [icon] and [icono]
* Added style attribute parameters 'style' and 'color'

= 0.1 =

Date: 09 Jan 2015
Dev time: 1 hour

* Initial plugin to add Icono stylesheet from http://saeedalipoor.github.io/icono/
