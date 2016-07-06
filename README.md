# COMP30680-Personal-Website
project realized for COMP30680 Web Application Development (University College Dublin), assignment 1 ([brief](COMP30680 Assignment 1.pdf))

Type of website: personal website

homepage: index.html
Gallery page: family.html
other pages: resume.html, projects.html, contact.html

Requirements:
* Link to own page: page "resume" at the bottom, there is a link to my "contact" page
* Link to external page: page "projects", there is a link at the bottom of the article to an external website
* Navigation bar: on top of each page
* At least 1 table: page "resume", see "skills" - this is a table
* At least 1 form: page "contact"
* At least 1 list: page "resume", see "education"
* At least 1 local or embedded video: page "projects"
* At least 2 CSS3 and HTML5 elements: "backgroung size" and "border-radius" for CSS3, 	"article" and "nav" for HTML5 (among others)
* Make use of the CSS positional properties (e.g. position, float): OK e.g. "position: relative;"
* Make use of both inline and block elements: OK e.g. "div" and "h1" for "block", "strong" and "img" for inline.


Own exploration of additional features of HTML and CSS:

* responsive design: the website has been designed so that it could run on laptops, cellphones and tablets. In order to make it compatible, size of block elements were defined in percentage rather than in px. The video (page "projects") was added as .mp4, .ogv and .webm to ensure compatibility. Moreover, because smartphones prevent autoplay of video, I had to add some Javascript to make it work. AS a result I have also added a poster picture so that user understand they need to click the video for it to play. The responsive design was sucessfully tested on Android (Nexus 5) and iPad. Compatibility with iPhone is supposed but not fully tested. The main challenge in making the site compatible cross-platform was the video element. Standards output achieved with a Nexus 5 and iphone 5 can be seen here: http://imgur.com/a/NPIAS
* Added overlay over pictures (page family)
* Image as background within the CSS (index, resume, contact)
* Exported fonts from the Google API (all pages)
* Used transparency (resume, contact) --> this was done so that the site is more attractive. There is more focus on the background HD picture.
* Efforts to make the website easy to read: content is centered, user access content based on scroll and not by looking at "another part" of their screen, no content displayed vertically (why: Banner blindness, F-shaped pattern cf https://en.wikipedia.org/wiki/Banner_blindness & https://www.nngroup.com/articles/f-shaped-pattern-reading-web-content/)
* Tried to make the website appealing to the eyes: use of high quality pictures in the background; pages generally symetrical (e.g. in the gallery all the pictures have the same ratio);



All content used is my own :-)
* Index: Slieve Leagues, county Donegal, 
* Resume: Dingle Bay, county Kerry
* Projects: my very own raspberry-pi / unicorn-hat powered color-clock
* Family: 11 pictures of my nephews (removed on GitHub - replaced by placeholders.)
* Contact: Achill Island, county Mayo
