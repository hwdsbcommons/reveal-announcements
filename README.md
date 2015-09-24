# reveal-announcements
A repository to explore the wp-rest-API and reveal.js to serve up announcements in D2L. Based on a HamOnt WordCamp presentation by Bentley Hoke http://www.bentleyhoke.com/brian-hoke-to-speak-at-wordcamp-hamilton/

https://github.com/bentleyhoke/wchamilton2015

Currently we have a number of WP sites feeding RSS widgets within D2L. This is ok, but it would be much more elegant to be utilizing WP as an authoring tool, feeding something nicer in D2L (like a reveal slideshow), without needing to rely on the RSS widget creator we are currently using (http://feed.mikle.com/) which at any time could go down, change their terms, etc. 

The code uploaded separates the posts by author. We would need each widget to pull from a separate blog, rather than an author. This may mean creating a separate widget for each school within D2L, and changing the index.php code appropriately. 

This all makes sense in theory, but I'm not sure how to implement it in practice, given some of the shortcomings of D2L. We may need to host the js separately (I'm hoping to be able to run it all from within the Shared Content folder in D2L.
