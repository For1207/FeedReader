# Project Overview

The goal of this project is to learn "testing-driven development" as an important part of web development process. I was given with a web-based application that reads RSS feeds and a starter code. The starter code includes [Jasmine](https://jasmine.github.io/index.html) - a main testing instrument for this project. Jasmine is an open source testing framework for JavaScript.

## The Tests List

1. Test to make sure that the `allFeeds` variable has been defined and that it is not empty.
2. Loop through each feed in the `allFeeds` object
and ensure it has a URL defined and that the URL is not empty.
3. Loop through each feed in the `allFeeds` object and ensure it has a name defined and that the name is not empty.
4. Ensure the menu element is hidden by default.
5. Ensure the menu changes visibility when the menu icon is clicked.
6. Ensure when the `loadFeed` function is called and completes its work, there is at least single .entry element within the .feed container.
7. Ensure when a new feed is loaded by the `loadFeed` function that the content actually changes.
8. Ensure when a new feed is loaded by the `loadFeed` function that the content actually changes.

## How to Run Tests
1. In the root folder of the project find and double click a file `index.html`.
2. It will open a new page in your browser with the RSS feed at the top and Jasmine at the bottom.
3. Jasmine section contains all tests. If a test passed successfully it will be green, otherwise - red.
4. All tests mentioned in the previous paragraph are in the file `feedreader.js`, which can be found at `FeedReader`>`jasmine`>`spec` folder.

## References

1. [Udacity Project Instructions](https://classroom.udacity.com/nanodegrees/nd001/parts/20f5a632-38e6-48e7-88c8-e14c21590bb9/modules/85de54c3-1646-44c5-9d81-228c05d9f3fc/lessons/3442558598239847/concepts/34300788080923)
2. [Feed Reader Testing starter code](https://github.com/udacity/frontend-nanodegree-feedreader)
3. [Jasmine Documentation](https://jasmine.github.io/)
