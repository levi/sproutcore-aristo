Cappuccino's Aristo for Sproutcore!

Install
-------

First cd into your app and do this:

	mkdir themes
	git clone git://github.com/stillmotion/sproutcore-aristo.git aristo_theme

Now add this to Buildfile:

	config :all,
	  :theme => :aristo_theme
	
	config :aristo_theme, 
	  :required => :empty_theme, 
	  :theme_name => 'aristo-theme'

Attribution
-----------

Aristo is an open sourceå UI distributed as part of the [Cappuccino Web Application Framework](http://cappuccino.org)
and specifically designed for the cross platform challenges applications face today.
It is a collaborative effort by [280 North, Inc.](http://280north.com/) and [Sofa](http://www.madebysofa.com/)
and released under the Creative Commons Attribution Share-Alike License.

You can view this license here: [http://creativecommons.org/licenses/by-sa/3.0/us/](http://creativecommons.org/licenses/by-sa/3.0/us/)

You can find out more about Aristo by visiting [http://cappuccino.org/aristo](http://cappuccino.org/aristo).

* 280 North, Inc., [280north.com](http://280north.com)
* Sofa, [madebysofa.com](http://madebysofa.com/)