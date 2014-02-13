less-debug-media-queries
========================

Media query debug mixin for Less is a very simple LESS snippet you can use to quickly debug your responsive website showing a little bar at the bottom of your page, displaying the media query is being fired.


usage
========================

Just copy the mixing, then trigger it into your media queries like the example below:

@media (min-width:800px){
	.mediadebug(lighten(yellow, 40%),"tablet")
}


@media (min-width:500px){
   .mediadebug(lighten(green, 40%),"phone")
}
