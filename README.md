DiscoverGists
=============

***DiscoverGists*** helps you (and the participants of WebGeneralisation) to discover GitHub-Gists visually!

*!!!Work in progess!!!*

### Files:
* index.html - Main page that enables the user to got to the:
	- Discovery of the basic Gists of the WebGen-project
	- Discovery of the Gists of a certain user

* discover_gists.html - Dynamic page, that visualises the thumbnails of all GitHub-Gists

### Background:
* inspired by the original idea of Mike Bostock: [bl.ocks.org](http://bl.ocks.org/)
* uses GitHub-API to [request the gists](http://developer.github.com/v3/gists/)
* uses an browser-oriented API-wrapper: [Github.js](https://github.com/michael/github)

### Utilization:
* the basis is a: [GitHub-account](https://github.com/login)
* load up one or more [GitHub-Gists](https://gist.github.com/)

* store these files in there:
	- thumbnail.png (ca. 200px * 100px)	--> if you want to have a nice preview
	- index.html 	--> if it is a web mapping snippet
	- readme.md 	--> if you've got some necessary remarks on your code