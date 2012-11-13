## Introduction

EmberBase is a collection of rich features you need outside the academic hoopla you will find on GitHub or redundant presentations on Speaker Deck, etc.  That is not what you will find here.  Using other ember projects, such as ember-data, and leveraging handlebars with support for mixins and SASS, this is the base site you should not only look to BUT contribute to.

Ember shouldn't scare off developers not familiar with Ruby or SproutCore, it's history is not as important as it's future.  This is very important because the adoption of ember is going to be reserved for those with a Mac that is running the correct version of Ruby and a lot of patience.  I don't mind doing some heavy lifting for my software team but I would rather people to write more code than hunt down exactly why they may or may not need RVM... Forget that!  Code on ember! 


## Getting Started

[ember-spark]() is a simple starter project is coming soon, like yesterday =]

For a bit more extensive example that uses all the features, see the [iHTML5os]().

## Licensing

Could be said that this is premature BUT currently this is released MIT style.  If you use some or all of this please just give myself or the LSDG a little credit.  DON'T STEAL what is free and clean box it for your own gain.  You will only be selling yourself as a developer short because someone smarter than you will ask why you did something a specific way and won't be able to answer.  Nothing worse then a semi competent developer who knows just enough to get in trouble or is too proud to ask for help.  Plus, we are watching you.... 

not really

## Features

All of the features that are current or being added to the ember-base project HAVE to support the following functionality:
 * two-way binding
 * responsive layout
 * touch/gestures

Available features/templates/widgets currently in ember-base:

 * Accounts
	- Account Objects and States
		+ Account Maintenance
		+ Account Creation/Signup
		+ Account Deletion/Unlink associated
		+ Password Reset
		+ Forgot Password
	- Account Templates and Implementations
	 	+ SAME AS ABOVE (objects and states)
	- OAUTH --> OAUTH1 & OAUTH2!
	- Third Party Implementations
		+ Custom (LDAP is used here BUT it can be whatever you want to roll <---HERE )
		+ Facebook
		+ Github
		+ Google
		+ Twitter 


## Responsive or Mobile First Design aka "MFD" 

This is a BIG MFD.....

320 and up is a great approach and EVERY FEATURE added to ember-base will be added with a mobile first mentality.  The goal of this project is to support modern day clients.  Notice I did not say browsers.... When I wrap ember-base projects up with PhoneGap or my own custom mobile device shell then we already know it has support for the nice HTML5 features we want to abuse, I mean leverage.  When I browse ember-base applications from a TV or other mediums the term browser is not really applicable.  If you get it you get it. 

## Layouts

Aside from a totally responsive design there might be instances where applications need fixed dimensions and restrictions.  FORK ME and get one started so that I can reference your project based on ember-base HERE...

## Handlebars Templates

Handlebars is semantically easy to work with and that's a plus.  Easy is not a requirement for any project but it sure is nice to have EASY and COMPREHENSIVE in parallel.  If there are other suggestions for supporting template libraries or how to provide a mechanism in this project to easily incorporate them please let me know.  


## The JIST

I would rather be writing code then scripting up this delicious README.MD file but I need an anchor out there on Github and really want to explain that this will be a very comprehensive project with WEEKLY code pushes/pulls to enhance existing features as well as deploy new ones.

This project will hopefully enhance other ember projects and only provide more exposure for EmberJS.

This project will develop against the 1.0 BETA until otherwise noted.  Clone, fork, contribute, criticize, etc --- ALL FEEDBACK IS WELCOME.


### Up next ... planned for November 2012

 * Realtime NodeJS Integration
 * Best In Class NoSQL hooks for RIAK (not Hadoop, not yet, too slow and messy)
 * Expanded Account Support for LinkedIn, etc
 * Expanded Features 
	+ D3 - if you know Mike Bostock tell him we need some contributors... nuff said.
	+ JQM and Bootstrap Themes.
	+ Bonsai (I LIKIE SVG ON CANVAS WITH DOM SUPPORT).
	+ GeoSpatial Magic aka MAPPING using OpenLayers, Leaflet, Polymaps.
	+ Expanded Styling capabilities with more SASS and STYLUS
	+ PubSub with Redis.
	+ Memory and Local Storage features including the use of MongoDB and Lawnchair.


## Contributing

Fork ember-base on GitHub, fix a bug or add a feature, push it to a branch in your fork named for the topic and send a pull request. 

You should also consider looking into contributing via The Lubbock Software Developers Group (LSDG).  Your a smart cookie so it is not likely your puny and pasty developer butt is going to be volunteering with Habitat For Humanity any time soon.... so use what you have, that brain. Code2Contribute and help the LSDG build amazing open source products for nonprofits across the country.

Fix an issue to break the seal: [issues](https://github.com/willcode2surf/ember-base/issues).
