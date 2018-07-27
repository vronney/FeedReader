# Project Overview

1. Edited the `allFeeds` variable in **./js/app.js** to make the provided test fail and see how Jasmine visualizes this failure in the application.   
2. Returned the `allFeeds` variable to a passing state.
3. Wrote a test that looped through each feed in the `allFeeds` object and ensured it had a URL defined and that the URL was not empty.
4. Wrote a test that looped through each feed in the `allFeeds` object and ensured it had a name defined and that the name was not empty.
5. Wrote a new test suite named `"The menu"`.
6. Wrote a test that ensured the menu element was hidden by default. Created variables 'body' and 'menuIcon' for testing hiding/showing of the menu.
7. Wrote a test that ensured the menu changed visibility when the menu icon was clicked. Created icon toggles to hide/show on clicking.
8. Wrote a test suite named `"Initial Entries"`.
9. Wrote a test that ensured when the `loadFeed` function was called and completed its work, there was at least a single `.entry` element within the `.feed` container.
10. Wrote a test suite named `"New Feed Selection"`.
11. Wrote a test that ensured when a new feed was loaded by the `loadFeed` function that the content actually changed.
