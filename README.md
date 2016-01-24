# Project Introduction 

For a given project that reads RSS feeds, I completed the test suite and make sure the current brach can pass all test cases.


## How to run
* Clone this branch to your localhost
* Open index.html to run the test
* To make changes and see how it works, open *./js/app.js* and make changes to the *allFeeds* object


## Steps
### All test cases are provided in *./jasmine/spec/feedreader.js*
* Wrote a test that loops through each feed in the allFeeds object and ensured it has a URL defined and that the URL is not empty.
* Wrote a test that loops through each feed in the allFeeds object and ensured it has a name defined and that the name is not empty.
* Wrote a new test suite named "The menu" that ensures the menu element is hidden by default and the menu changes visibility when the menu icon is clicked
* Wrote a test suite named "Initial Entries" that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
* Wrote a test suite named "New Feed Selection" that ensures when a new feed is loaded by the loadFeed function that the content actually changes.

