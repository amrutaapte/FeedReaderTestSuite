# FeedReaderTestSuite

# Project Overview

Wrote test suites for an existing application that reads RSS feeds. The tests run on various functionality of the Feeds page.


## To run the test suite

Jasmine framework has been included in the project files.
To run the application and test suite, load the index.html file in your browser.

# How I completed this project

1. Took the JavaScript Testing 
2. Downloaded the required project assets
3. Reviewed the functionality of the application within browser
4. Explored the application's index.html, CSS and JavaScript to gain an understanding of how it works
5. Explored the Jasmine spec file and reviewed the Jasmine documentation
6. Edited the `allFeeds` variable in to make the provided test fail
7. Returned the `allFeeds` variable to a passing state
8. Wrote a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty
9. Wrote a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty
10. Wrote a new test suite named `"The menu"`
11. Wrote a test that ensures the menu element is hidden by default
12. Wrote a test that ensures the menu changes visibility when the menu icon is clicked
13. Wrote a test suite named `"Initial Entries"`.
14. Wrote a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container
15. Wrote a test suite named `"New Feed Selection"`
16. Wrote a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes
