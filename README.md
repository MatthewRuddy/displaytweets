=== Display Tweets  ===
Homepage: http://matthewruddy.com/display-tweets-plugin/
Contributors: MatthewRuddy
Tags: twitter, tweets, feed, retweets, mentions, favourites, display
Requires at least: 3.5
Tested up to: 3.5.1
Stable tag: 1.0

"Display Tweets" is an easy to use Twitter feed plugin that uses the v1.1 Twitter REST API.

== Description ==

A rather simple Twitter feed plugin that fully supports the Twitter v1.1 REST API. Authenticated requests are made using PHP to retrieve tweets. It's fully future proof, so no disappearing feeds when the old Twitter REST API is turned off.

Some WordPress actions have been included to make overriding the feed's HTML easy. For more information, <a href="">see this page</a>.

== Installation ==

Using the plugin is easy. There are three ways to display your feed.

Shortcode:
`[display_tweets]`

PHP Function:
`<?php if ( function_exists( "display_tweets" ) ) { display_tweets(); } ?>`

You can also display your tweets using the included widget.

== Screenshots ==

1. The Twitter feed settings panel.
2. A snapshot of tweets displaying.