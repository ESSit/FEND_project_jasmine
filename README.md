## Project Overview

This project has a web application that reads RSS feeds.
Which has test based on "Jasmine"(http://jasmine.github.io/).

### There are 6 test within 4 group.

1 - Group "RSS Feeds" has the tests:
- Are Defined
- URL defined and value url not empty in allFeeds object

2 - Group "The menu" has the tests:
- Body hidden by default
- Click menu test

3 - Group "Intial Entries" has the test:
- loadFeed() its work

4 - Group "New feed Selection" has the test:
- Changes content loadFeed() is asynchronous

### What tests do?

Are Defined:
- Make sure that the allFeeds variable has been defined and that it is not empty.

URL defined and value url not empty in allFeeds object:
- Loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
- Loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.

Body hidden by default:
- Ensures the menu element is hidden by default.

Click menu test:
- Ensures the menu changes visibility when the menu icon is clicked. This test have two expectations: the menu display when clicked and it hide when clicked again.

loadFeed() its work:
- Ensures when the loadFeed() function is called and completes its work, there is at least a single .entry element within the .feed container.

Changes content loadFeed() is asynchronous:
- Ensures when a new feed is loaded by the loadFeed function that the content actually changes.

### How to Start the app:
- Open the index.html file in your browser.

Test result will be at the bottom of the page.
