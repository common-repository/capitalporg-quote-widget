=== CapitalP.org Quote Widget ===
Contributors: trepmal
Donate link: http://kaileylampert.com/donate/
Tags: widget, capitalp.org, capital_P_dangit
Requires at least: 3.3
Tested up to: 4.2
Stable tag: trunk

Grab a quote from capitalp.org, display it.

== Description ==

Grab a quote from capitalp.org, display it.

Has shortcode! `[capitalp]`

== Installation ==

1. Install just like a any other plugin
1. [See Codex](http://codex.wordpress.org/Managing_Plugins#Installing_Plugins) if you need to.
1. Find 'CapitalP.org Quote Widget' on the widgets page

== Frequently Asked Questions ==

= Why? =

Why not?

== Other Notes ==

= Shortcode & Template Tag =

 `[capitalp]` or `get_capitalp_quote();` returns

`
<blockquote><p>The Capital “P” in WordPress <b>is a horse designed by committee.</b></p><p><cite><a href="http://capitalP.org/">capitalP.org</a></cite></p></blockquote>
`

 `[capitalp cite=0]` or `get_capitalp_quote( true, false );` returns

`
<blockquote><p>The Capital “P” in WordPress <b>doesn’t search before asking questions in forums.</b></p></blockquote>
`
 `[capitalp markup=0]` or `get_capitalp_quote( false );` returns ('markup' overrides 'cite')

`
The Capital “P” in WordPress <b>plays Angry Birds at full volume on the bus.</b>
`

== Screenshots ==

1. Widget options
2. What it looks like in Twenty Eleven's footer

== Upgrade Notice ==

= 0.2 =
The shortcode cometh

== Changelog ==

= 0.5 =
* maintenance

= 0.4 =
* 2015 checkin. Cleanup, longer transients
* Drop the markup attr from the shortcode
* Add a filter for optionally customizing the markup

= 0.3 =
* Using transients to cache (up to 15 minutes)

= 0.2 =
* The shortcode cometh

= 0.1 =
* It haseth beeneth releasedeth.