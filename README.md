# FWD - Landing Page

Professional Track - Project #1

## Description

-This is a landing page project, its code is written in HTML, CSS and JavaScript files.

-The HTML & CSS files represent the static version of the webpage while modifying the JS file adds all the dynamic properties and functionality to it.

-The navigation bar starts as an empty unordered list. The list items and their properties, HTML, CSS are added by JS.

-If a section is added through the HTML file, It'll automatically be added to the webpage as well as all its functionalities.

## Usage

A dynamic responsive webpage. The navigation bar has a list of sections. When the user clicks on any desired section, the page will scroll down *smoothly* to the section he clicked on from navigation bar.
In addition to when the user is scrolling down, the section he's reading (section in view) will be **highlighted** differently than other sections.

## This project depends mainly on two things:

1-Which section is the user viewing.

2-Which section did the user click on from the navigation bar.

Because here lies the main functionality of the program:

-While the user is viewing a section, the CSS of this section changes from default by adding active class to it. Once he scrolls down to another section, the old section returns to default CSS and the active class is removed and added to the section which he is currently viewing and so on. The CSS is changed upon adding and removing the active class from a section and this all depends on which section the user is reading or viewing.

-When the user clicks on a specific section from the navigation bar, the page will automatically and smoothly scroll down to this section. At first, the main functionality of this only made the page jump to the clicked section but this was solved when an event listner is added to the navigation bar, when the user clicks on an item, the default behaviour of jumping is removed and instead it scrolls down smoothly after waiting a very short time.

Check it out: https://hadirwahidd.github.io/FWD---Landing-Page/
