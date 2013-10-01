=== Simple Google News ===
Contributors: (KevinSpence)
Donate link: http://kidvolt.com/
Author URI: http://kidvolt.com/
Plugin URI: http://kidvolt.com/simple-google-news
Tags: google, google news, rss, feed, news
Requires at least: 2.5
Tested up to: 3.6.1
Stable tag: 1.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Easily add Google News search results to posts or pages on your WordPress site.

== Description ==

The 'Simple Google News' WordPress plugin makes it easy to display Google News results on your WordPress site’s posts or pages by using the following shortcode:

[google_news]

==Available Parameters==

There are a handful of optional parameters that you can use to customize the output to your liking. 

**query** – *Default: none*. Use this you want to search Google News for a particular word or phrase.

**limit** – *Default: 5, Max: 10*. Using the ‘limit’ parameter, you can set the maximum number of results that you would like to display on your post or page.

**images** – *Default: on*. Images are turned on by default. If you would like to turn them off, set the images parameter to ‘off.’ Note: Not all news stories will have an image.

**length** – *Default: 200*. The length parameter lets you control how many characters of the description (rounded to the nearest complete word) should be shown.

**region** – *Default: us*. With the ‘region’ parameter, you can choose to show news from a particular part of the world. To see the list of currently supported regions, visit [link](https://support.google.com/news/answer/40237?hl=en "this page"). Note the ‘ned’ parameter that's present in each region link. For example, India’s ned parameter is set to ‘in’. That is the value you would use to display news from that particular region.

**topic** – *Default: none*. If you want to display news by topic (ie: technology, entertainment, etc), you can do so with this parameter. For example, if you wanted to show technology results, you would set your shortcode to something like this:

[google_news limit="2" topic="t"]

Note: the topic parameter overrides the query parameter. So if you tried to do something like:

[google_news query="android" topic="t"]

Google News would ignore the query.

Here are the acceptable topic values:

b (for business)
t (for technology)
e (for entertainment)
s (for sports)
snc (for science)
m (for health)
ir (for spotlight)

== Installation ==

1. Upload the 'simple-google-news' directory to the '/wp-content/plugins/' directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Place the [google_news] shortcode in your posts or pages

== Frequently Asked Questions ==

= I'm using the shortcode and nothing is happening! =

A couple things could be going on. First, your search may not be returning any results. Verify that the search is good by visiting news.google.com and trying your search there. Second, you may have provided some invalid values for the shortcode parameters. Doublecheck them.

= Can I use a shortcode in a widget? =

No. But if there is enough interest, I will consider working on a widgetized version of this plugin.

== Screenshots ==

1. This is a screenshot from my site, where I've used the shortcode to display news about Google.

== Changelog ==

This is the first release. Nothing to report.

== Upgrade Notice ==

No reason to update yet, as this is the first release.
