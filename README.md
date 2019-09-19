# Game of Thrones for Android Challenge

Android developers face challenges almost everyday during development: performance, security, backwards compatibility, testing... And mainly refactoring for it's own or legacy code.
This repository contains a project description to face a small challenge where the developer should build the app along with some new features, detect (and implement) patterns, add tests, and do a clean code.

Game of Thrones for Android Challenge offers an app using an API to get data for [Game of Thrones][gameofthroneslink] tv show. Your challenge is to build the app however you see fit!

## Getting started

Your task is to build an app that retrieves a list of some [Game of Thrones][gameofthroneslink]' characters from an API. The app shows a list of the houses of the characters, the characters themselves and a detail description of each one.

API URL: https://android-challenge-3472e.firebaseio.com/characters.json?print=pretty

This behaviour should be done in two diffent [Activities][activitylink], one for the two lists and other for details of the character:

![ScreenshotListCharacters][screenshotlistcharacters]![ScreenshotListHouses][screenshotlisthouses]![ScreenshotDetail][screenshotdetail]

-   `HomeActivity` should contains two [Fragments][fragmentlink] in a [ViewPager][viewpagerlink]

    -   `GoTListFragment` shows a list of some the this tv show's characters.
    -   `GoTHousesListFragment` shows a list of the noble houses of the characters

-   `DetailActivity` shows the name, photo and description of a character

## Tasks

Your task as Android Developer is build your application, test and refactor your code before you give access to your repository.

###### Functionalities to be included

1. Search characters by name in the characters list
2. Create a list of a characters by house, accessing to it by clicking a house image in the list of houses
3. Capability to work offline
4. Add transitions between list and detail (Optional)

###### Once you've finished

1. Generate the application apk and push the code to a Github repository
2. Notify by email to bassem.mawhoob@live.com with the link of the Github repo and a list of functionalities you implemented
3. Have some rest!

[screenshotlistcharacters]: ./art/ScreenshotListCharacters.png
[screenshotlisthouses]: ./art/ScreenshotListHouses.png
[screenshotdetail]: ./art/ScreenshotDetail.png
[activitylink]: http://developer.android.com/intl/es/guide/components/activities.html
[fragmentlink]: http://developer.android.com/intl/es/guide/components/fragments.html
[gameofthroneslink]: http://www.imdb.com/title/tt0944947/
[viewpagerlink]: http://developer.android.com/intl/es/training/animation/screen-slide.html
