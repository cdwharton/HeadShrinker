HeadShrinker v1.0.1
=====

For shrinking your website header, not your actual head!


Demo
----
[http://weare2ndfloor.com/headshrinker/](http://weare2ndfloor.com/headshrinker/)


Dependencies
------------

* [jQuery](https://github.com/jquery/jquery)


Set up
----
Nice and easy, just include this in your &lt;head&gt; or just before &lt;/body&gt;

	<script src="http://code.jquery.com/jquery-10.1.2.js"></script>
	<script src="jquery.headshrinker.js"></script>
	<link rel="stylesheet" href="headshrinker.css" media="screen" />

Then call the function…

	<script>
		jQuery(document).ready(function () {
    		jQuery('header').headshrinker();
	});
	<script>

Options
---
	target: jQuery(this), // set target
	zindex: 99999, // set CSS z-index
	shrinkBy: 2, // shrink by this multiple
	fontSize: "", // add font size in here
	shrinkMenu: false, // convert menu to hamburger in all instances
	revealAlign: "right", // left or right hamburger menu
	revealTop: "12px", // adjust top positioning of hamburger menu
	shrinkMenuTop: "69px", // adjust top positioning of the flyout menu
	menuSwitch: 768, // aimed at the mobile experience, when menu is this width, convert to hamburger
	navTarget: 'nav', // this is the element WITHIN the cloned headshrinker bar
	mobileMenu: false // set to true if you want to remove the desktop menu and replace with headshrinker when in mobile view (menuSwitch)
            
