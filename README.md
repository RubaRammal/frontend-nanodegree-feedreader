# Project Overview

This project is part of Udacity's frontend nanodegree. The goal is to write test suits using Jasmine for an application and to ensure that all tests pass successfuly.


## Getting started

To run the page, download or clone the repository and click at `index.html`. After the feed load, scroll down to view Jasmine's specs. The text in green indicates that tests passed and the tests in red indicates the fail of tests.


## Test cases

The following explains the tests cases created against the existing application:

1. `allFeeds` is defined: if it contained no item or if it was not defied the test will fail. 
2. `name` and `url` properties of `allFeeds` are defined: if their values were null or empty the test will fail.
3. The menu is hidden by default: the `body` element should initially have the class `menu-hidden` or the test will fail.
4. The menu changes visibility when the menu icon is clicked: test will pass if icon click toggled class `menu-hidden` from the `body`.
5. The feed container should contain at least one entry: after the asynchronous call is loaded, the `.feed` class must have more than zero `.entry` children.  
6. New feed should be loaded: if the new feed content matched the previous feed content, the test will fail.
