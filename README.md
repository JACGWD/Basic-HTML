# Basic-HTML
Basic HTML template used as the basis of web classes above Web III at GWD.

Note that the base HTML is that from the [HTML 5 Boilerplate project](https://github.com/h5bp/html5-boilerplate). The difference here is that the basic template is heavily commented for ease of use by beginners. The advanced template contains many metatags for SEO and social media optimizations.

##Master Detail Pages
This folder contains two HTML files. They are both based on the base.html file.

Many people find the names "master/detail" a bit confusing although it is a standard term used in programming. It is for example easier to understand the relationship if you call it "category/product" or "products/item". Note the basic pattern is "multiple things/one single thing".

In a graphic arts portfolio this could be "print projects/business card" and "print projects/poster".

The only code difference in between a master and detail page is the number of thumbnails/links. A "master" page has many links/thumbnails that point into a *set of related pages*, where one of those pages has only one thing on it.

For example, a master page would have multiple images and links to a set of products such as groceries.html. Each detail page would be one single item from that list, such as milk.html or orange-juice.html. By default, the master page has a lot of information on it and points to a page with specific information about one thing.

Another example would be beatles-albums.html pointing to rubber-soul.html and white-album.html (and several others of course).

###Search Engine Optimization
Note that *detail pages are important for SEO (search engine optimization)* because they are very *specific*.

Example: If you have a page called pets.html that has info about ten animals on it: cats, dogs, turtles, fish, ... etc. If someone does a Google search looking for "turtles" then your page is only 10% relevant.

If you have a master page called pets.html *and* and page called turtles.html then turtles.html is 100% relevant to the Google search and your page is likely to be seen.

Remember that the [best place to hide a dead body is on page two of Google](https://duckduckgo.com/?q=best+place+to+hide+a+dead+body+is+on+page+two+of+Google&t=ffnt&ia=web). 
