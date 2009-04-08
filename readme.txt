=== Review Box ===
Contributors: paradox460
Tags: review, rating, box, post, cons, pros, score
Requires at least: 2.5
Tested up to: 2.7.1
Stable tag: 1.0

Provides a simple shortcode to generate a box for writing reviews. Supports pros, cons, and a numerical score.

== Description ==

Provides a shortcode for use by reviewers.

Generates a box, for use in a post or page, with a section for Pros, a section for Cons, and a review bar.

The review bar is generated through CSS, and so the plugin contains **NO** images.


== Installation ==

1. Upload the `review-box` directory to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. In a post, place `[review pros="list of pros" cons="list of cons" score=75]` where you would like the box to appear

== Frequently Asked Questions ==

= Do i have to fill out all 3 properties =

No, but it is reccomended. If you do not fill them out, they will have a default value.

The default values are fairly amusing.

If you do not fill out the score value, the plugin will default to 100

= What format should the score value be in =

The score should be an integer between 0 and 100. It will ultimately come out as a percentage.
**The score does not need a % sign following it. Adding one will make the sky fall on your head**

== Usage ==
This plugin generates a simple shortcode to use.
That shortcode is `[review pros="" cons="" score="`

The paramiters are required for proper output.
They are as follows
* **pros:** Anything you find good about the item being reviewed. Typically a comma seperated list
* **cons:** Anything bad about the product at hand. A comma seperated list as well
* **score:** This **MUST** be a number. There can be nothing following it, nor anything before it. A good example of the way to fill it out would be `score=45` for an item that scored 45%