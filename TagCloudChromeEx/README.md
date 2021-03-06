# TagCloud Extension
=================

## Installation

You can now install this extension from the chrome webstore [here](http://goo.gl/pQHts): just follow instructions, allowing the required permissions, and you'll be ready to go!

## Usage

Once installed, all you need to do is to click on the extension icon next to the address bar and a popup window will open,
showing you the Tag Cloud with the most used words in the current page and a search bar that will allow you to search any
content on several search engines (Google, Twitter, Facebook, Quora and Wikipedia at the moment).

By clicking on any tag in the tag cloud, you'll be able to add its text to the search bar, instead of typing it.

## Version 1.0.0

Right click functionality added on selection: you can search the selected text with the same search engines as above, 
and translate it with Google Translate.


## Version 0.2.1

This is a simple extension, based on AngularJS framework, that, each time it is activates, 
parses the currently shown page and creates a Tag Cloud with the 100 most used words in it (100 is by default, but can be set to any number).

Once the Tag Cloud is shown, every Tag can be clicked and its text will be added to a search bar above the tags: 
then the content of the search bar (which is, of course, also editable) can be then searched for on Google, Twitter, Facebook or Quora.

## Acknowledgments
This extension is based on a few libraries, so there are a number of people I'd like to thank for their work:

* *AngularJS* team, for their amazing work on this great tool;
* *JQuery* team, for the same reason above;
* Mike Bostock, for his *D3js* library (really awesome);
* Jason Davies, for his *Word Cloud* plugin for _D3_;