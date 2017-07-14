=== Movie Data from RT ===
Contributors: creativecreate
Tags: rotten tomatoes, movie, movies, movie database, movie library, movie collection, cinema, movie genre, movie image, movie poster, movie meta, movie metadata
Requires at least: 3.8
Tested up to: 4.4
Stable tag: 1.0.4
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Display list of movies (with Title, Year, Rating, Poster, Description etc.) from "Rotten Tomatoes".

== Description ==
= What it's for ? =
MovieDataFromRT plugin generates a list of movies based on four categories - "Box Office", "In Theaters", "Opening Movies" and "Upcoming Movies" from Rotten tomatoes'. Simply select the type of movie category you want and you're done. All movie data - Title, Year, Rating, Critics/Audience Score, Description and poster image - automatically fetched and assigned to your movies.

Whether you want to display a simple movie list or turn your WordPress into a professional looking movie blog, MovieDataFromRT plugin's flexible column design, Informative tooltips, comprehensive short-code list and user friendly widget will make your tasks easier.

= Important Note: The sole purpose of this plugin =
This plugin uses Rotten Tomatoes (RT) API and only registered user with Rotten Tomatoes, who already have credentials can access to feeds. User need to enter Rotten Tomatoes' API Key ( [Register Here with RT](http://developer.rottentomatoes.com/docs) ) in order to access data through this plugin. This plugin doesn't have any ties to RT and it's only parses and read the API, XML content. Using these parsed data within terms of RT is responsibility of the user. Please view the [Rotten Tomatoes Terms](http://www.rottentomatoes.com/terms) for more details.

= Demo =
[Click here to see a demo](http://wp.creativecreate.com/)

= Features =
* Custom Dashboard
* One click Movie List generate (Box Office, In Theaters, Opening Movies and Upcoming Movies)
* Automatic metadata import: Title, Year, Rating, Critics/Audience Score, Description and Poster Image
* Layout configurations : Number of columns, movies
* Informative tooltips (on/off)
* Toggle Poster Image quality (hi-res vs low-res)
* Link to detailed movie-page at rottentomatoes.com 
* Widget and flexible configurations to display the list within the sidebar
* Short-code with layout options to manage placement of your list 
* Much more!

= Get involved =
Contribute to the source code on the [GitHub](https://github.com/CreativeCreate/RTMovieDataPlugin.git).


== Installation ==
= Minimum Requirements =
* WordPress 3.8 or greater
* PHP version 5.3 or greater (5.4 recommended)
* MySQL version 5.0 or greater

= Installation via WP Dashboard =
To install MovieDataFromRT via dashboard use the WordPress Extensions installer. From your WordPress dashboard, go to the Plugins page and hit "Add New". In the search field type input "MovieDataFromRT" and click "Install" and then active.

= Manual installation =
* Download the plugin from the WordPress.org Repository
* Unzip the plugin archive file
*Upload the plugin folder to the `/wp-content/plugins/` directory via FTP
*Activate the plugin through the WP Dashboard > \'Plugins\' menu in WordPress

== Frequently Asked Questions ==
= What does it do? =
Movie Data from RT is a plugin that helps you to generate list of movies with meta data. Note that this plugin does not save movie data as post.

= How does it work? =
MovieDataFromRT plugin generates a list of movies based on four categories - "Box Office", "In Theaters", "Opening Movies" and "Upcoming Movies" from Rotten tomatoes'. Simply select the type of movie category you want and you\'re done. All movie data - Title, Year, Rating, Critics/Audience Score, Description and poster image - automatically fetched and assigned to your movies.

= Is this legal? =
This plugin uses Rotten Tomatoes (RT) API and only registered user with Rotten Tomatoes, who already have credentials can access to feeds. User need to enter Rotten Tomatoes' API Key ( [Register Here with RT](http://developer.rottentomatoes.com/docs) ) in order to access data through this plugin. This plugin doesn't have any ties to RT and it's only parses and read the API, XML content. Using these parsed data within terms of RT is responsibility of the user. Please view the [Rotten Tomatoes Terms](http://www.rottentomatoes.com/terms) for more details.

= Can I use another API? =
No, at least not directly. Movie Data from RT uses Rotten Tomatoes API only.

= Do I need an API key? =
Yes. This plugin uses Rotten Tomatoes (RT) API and only registered user with Rotten Tomatoes, who already have credentials can access to feeds. User need to enter Rotten Tomatoes' API Key ( [Register Here with RT](http://developer.rottentomatoes.com/docs) ) in order to access data through this plugin. This plugin doesn't have any ties to RT and it's only parses and read the API, XML content. Using these parsed data within terms of RT is responsibility of the user. Please view the [Rotten Tomatoes Terms](http://www.rottentomatoes.com/terms) for more details.

= My movies don't show in my homepage/slider/widget =
There is a chance your theme/plugins are not compatible (This plugin should work with most themes.) open a thread in the support forum to get some help.

= Can I display other lists from RT such as DVDs, TV Shows etc? =
No. As its name implies, Movie Data from RT is about displaying movie lists, and was never meant to include DVDs and TV Shows etc.

== Screenshots ==

1. Admin Dashboard
2. Widget Settings
3. Widget display: 1 Col | 2 Cols | 3 Cols
4. In Post/Page view (shortcode) 
5. In Post/Page view (shortcode with options)

== Changelog ==

= 1.0.4 =
* Fixed hi-res loading issue. Now hi-res loads only if it's available

= 1.0.3 =
* Fixed stylesheet not loading issue

= 1.0.0 =
* First stable release

