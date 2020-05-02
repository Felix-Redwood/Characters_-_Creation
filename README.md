Characters & Creation:
======================

Characters & Creation (C&C) is a website seeking to provide simple explanations of the features of the classes, races and feats found in D&D 5th edition. By providing qualitative descriptions of these features, instead of number-heavy and rule-heavy descriptions, C&C seeks to be able to guide beginner players into deciding what class and race they wish to play in their D&D games, as well as helping beginner dungeon masters to understand the role that each race and class plays in D&D.

In this README, there is a list of requirements and recommendations for submitting homebrew content, which will be added to the site in future. Submitting homebrew content is recommended only for more experienced players or dungeon masters, and so uses language that might not be known to newer players. 

UX:
---

This website is primarily designed for those who are beginners when it comes to D&D or role-playing games in general, however it is also designed to benefit other users, such as:

* Dungeon masters or players who are seeking to refresh their knowledge on classes or races other than the ones that they tend to play.
* Dungeon masters or players who are moving their game to D&D 5e (5th edition) from another role playing game (such as pathfinder) with different rules, who wish to gain an understanding about the features of the classes and races of D&D 5e.
* Players who generally play one specific class or race, but are looking to play a different class or race in a new game.
* Players who have chosen a race to play but cannot decide what class they should play alongside it, and vice versa.
* Players who have created a character without any idea of their class or race, and now must decide what class or race fits that character best.
* Dungeon masters who are trying to create NPCs (non-playable characters), and are seeking to decide what race or class the NPCs will be.

In terms of these users, each one will have a certain desire:

* As a beginner player, I want to read a simple but informative and compelling description of the classes and races of D&D 5e, so that I can figure out what class and race I want to play, and how they fit into the world and story of my games.
* As a dungeon master, I want to read a simple but informative and compelling description of the classes and races of D&D 5e, so that I can create NPCs that my players will enjoy interacting with, and so that I can help create a world that my players enjoy and that makes sense.
* As a player going into a new game, I want to read a simple but informative and compelling description of the classes and races of D&D 5e, so that I can figure out what class and race fits in best with my ideas about my new character.

As you can see, what this site’s visitors desire is for the descriptions of each class and race to be simple, so that players and DMs (dungeon masters) don’t have to take a large amount of time to read it, informative, so that players and DMs can have enough knowledge about the roles and features of each class and race to implement them to their desire, and compelling; D&D is supposed to be a fun, exciting game, and by writing the classes and races in a compelling way, players will feel more excited about the characters they create, and DMs will be able to create more interesting, diverse NPCs for the players to interact with.

[Roughly 60% of the population are visual thinkers in one way or another](https://books.google.de/books?hl=de&id=LXEezzccwcoC&q=Visual+thinking#v=onepage&q=Visual%20thinking&f=true). This means that the descriptions of the races, classes and feats of D&D must be visually descriptive, to help newer players especially to visualise what their characters might look like or do.

Features:
---------

Existing features:

* Description of races & classes for D&D with recommendations of which races and classes to pair together.
* List of all Feats from the PHB (the player’s handbook, the official basic source material for 5th edition D&D).
* Easy navigation between pages.
* Link to WOTC in footer (wizards of the coast, the owners of the D&D 5th edition material).
* Link to my email (felix@grahamredwood.com) in footer, so that people can send in suggestions.
* Meta tags in the <head> element for the purposes of SEO.
* Favicon used to increase user experience and help the user distinguish the tab that C&C is being run on.

Features that will be implemented in future:

* Contents menu and collapsible descriptions for the races, classes and feats pages, as currently they are hard to navigate.
* Pictures of each race and class next to their descriptions, to aid visualisation.
* Possibly, pictures of feats being used, such as a person wearing heavy armour for the ‘Heavily Armoured’ feat, or of a person charging forward for the ‘Charger’ feat.
* A page of homebrew (player created) content.
* A page listing all backgrounds from the PHB.

Technologies used:

* [W3schools](https://www.w3schools.com/).
* W3schools was used to find hexadecimal colours to use for the site, as well as assisting with debugging code.

* [Bootstrap](https://getbootstrap.com/).
* Bootstrap was used as a CDN, and styles most of the site.

* [Font Awesome](https://fontawesome.com/start).
* Font Awesome was used to provide the menu icon in the header.

* [Google fonts](https://fonts.google.com/).
* Google fonts provided the fonts for the site.

* [HTML](https://html.com/).
* Used to code the divs, text and other elements on the site, as well as providing meta tags.

* [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets).
* CSS was used to style the elements in the site.

* [Cloud9 (AWS)](https://aws.amazon.com/cloud9/).
* Cloud9 was where the site’s code was written and stored. 

* [Github](https://github.com/).
* Github was used to host the code and act as a repository and backup for the written code.

* [Logomakr](https://logomakr.com/).
* Logomakr was used to design the C&C logo.

Testing:
--------

The main UX to focus on with the site is readability, ease of use and interconnectedness. For this reason, I ran three tests:

  

Test 1 – ensuring that any class, race or feat can be found quickly:

* Start on homepage
* From here, you can click on the hamburger icon to the right in the menu, however on the main page there are clear, bold links to the races, classes and feats pages.
* Click on one of these links.
* Scroll down. Each segment of text has a different background colour and font colour of the segments above and below it, allowing it to be easily distinguished. Additionally, the titles of each segment are larger than the text itself, meaning that it is easy to find what you’re looking for.  

  

Test 2 – ensuring that people can contact me easily:

* Start on homepage.
* In the characters & creation description, just under the homepage links, my email is highlighted in green, to stand out from the background of grey. Additionally my email is in the footer (where it is usually located on most sites), in bright blue, as a stark contrast to the dark background.  

  

Test 3 – ensuring easy navigation:

* Start on homepage.
* Attempt to access the ‘Feats’ page. This can be done by clicking the homepage links or the links in the dropdown menu in the header. Additionally, there is a link to the ‘Feats’ page in the characters & creation description on the homepage.
* From here, attempt to access the ‘Races’ page. This can be done by clicking on the ‘Races’ link in the dropdown menu in the header.
* From here, attempt to navigate back to the homepage. This can be done by clicking the logo in the header, or by clicking the ‘Home’ link in the dropdown menu in the header, which is separated from the other links by a divider.

Homebrew submission requirements:
---------------------------------

Homebrew submissions must:

* Have been play tested to ensure balance (no underpowered/overpoweredness).
* Scale reasonably in power and abilities with the player’s level.
* Not be unreasonably complicated.
* Adhere to the rules laid out in the PHB, and not invent rules of their own.
* Have ASIs (Ability score increases) at least at levels 4, 8, 12, 16 and 19.
* Not have unreasonable requirements for play (e.g. requiring a certain alignment or for the player to possess certain equipment).
* Not provide the player with starting equipment if the homebrew submission is a race.
* Detail the saving throw proficiencies, tool, weapon and armour proficiencies and skill proficiencies given if the homebrew submission is a class.

It is recommended that homebrew submissions:

* Come with a list of recommended classes or races to play in conjunction with the homebrew class or race.
* Explain the prerequisites for multiclassing (if the submission is a class).
* Do not have a hit die higher than a D12 or lower than a D6.
* Do not grant abilities that are exclusive to certain PHB classes (such as the barbarian’s rage or the druid’s wild shape), as this will invalidate those PHB classes.

Deployment:
-----------

This project is hosted on github pages. At the time of the submission of this README (20th of December, 2019), the deployed version and the development version are the same, with the same code and the same README. If this changes in the future, this README will be updated.

The code can be run locally either by visiting the website directly through the URL [https://felix-redwood.github.io/Characters_-_Creation/](https://felix-redwood.github.io/Characters_-_Creation/) or by viewing the project in [github](https://github.com/Felix-Redwood/Characters_-_Creation) and copying and pasting the code into a program that will run it.

FAQ:
----

Q: Will you keep working on the site?  
A: Yes! There are a lot of additions to the site I plan to make.

Q: How can I contact you?  
A: My email is felix@grahamredwood.com. It is posted in the footer of the site and clicking on that link will open an email addressed to me.

Q: Why don’t you have proper statistics or descriptions of rules, etc?  
A: This site is generally designed for newer players or DMs, and focuses more on the descriptions, aesthetics and roles of the different races and classes instead of their mechanics or statistics. This is so that newer players/DMs don’t get overwhelmed by the amount of information thrown their way.

Q: Are you on social media?  
A: Not yet. At the moment I’m going through some lifestyle changes and focusing on a couple of other projects. For this reason, characters & creation has no social media accounts as I couldn’t ensure regular posting. I think that in the future I’ll create a Twitter account and a Facebook page for C&C. When I do, I’ll put links in the footer of the site.

Credits:
--------

Content:

* The text for the page ‘Feats’ was copied from [http://www.jsigvard.com/dnd/Feats.html](http://www.jsigvard.com/dnd/Feats.html)
* The information about D&D races and classes came from the ‘[5e character](https://play.google.com/store/apps/details?id=com.dungeon.dev.a5echaracter&hl=en_US)’ app by Dungeon Dev on the Google Play store.
* The base code and classes were taken from the Code Institute Whiskey Drop site that I was helped to build.

Media:

* The background image for the site was taken from: [(https://www.directupload.net/file/u/15382/mdqvbx4k_jpg.htm)](https://www.directupload.net/file/u/15382/mdqvbx4k_jpg.htm)
* The logo for the site was designed by me on [https://logomakr.com/](https://logomakr.com/)

Acknowledgements:

* I received inspiration for this project from the [critical role](https://www.youtube.com/channel/UCpXBGqwsBkpvcYjsJBQ7LEQ) cast:.
* I gained the necessary knowledge of coding required to make this site from the [Code Institute](https://codeinstitute.net/), Dublin and their Full Stack Web Developer course.
