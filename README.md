# Feed-Reader-Testing
# Project Overview
In this project I was given a web-based application that reads RSS feeds. The original developers of this application have already included Jasmine and even started writing their first test suite! My task is to write test suites that test functionality of certain elements of the application.
I used the Udacity forums and Udacity JavaScript testing course to complete this project. All work for this project was done in feedreader.js .

# Tests
1. A test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
2. A test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
3. A new test suite named "The Menu".
4. A test that ensures the menu element is hidden by default.
5. A test that ensures the menu changes visibility when the menu icon is clicked.
6. A new test suite named "Initial Entries".
7. A test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
8. A new test suite named "New Feed Selection".
9. A test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.

# How to run
By using terminal:
git clone https://github.com/HAJennifer/Feed-Reader-Testing.git
- Open index.html with your browser.
- There should be 8 specs, 0 failures at the bottom of the html page.
