Rally Story Board
============

![Title](https://github.com/RallyApps/StoryBoard/raw/master/screenshots/title-screenshot.png)

## Overview

The Story Board app provides your team a view of the stories, defects and defect suites within your iteration organized by schedule state, as if you were looking at a white board.

## How to Use

### Running the App

If you want to start using the app immediately, create an Custom HTML app on your Rally dashboard. Then copy App.html from the deploy folder into the HTML text area. That's it, it should be ready to use. See [this](http://www.rallydev.com/help/use_apps#create) help link if you don't know how to create a dashboard page for Custom HTML apps.

Or you can just click [here](https://raw.github.com/RallyApps/StoryBoard/master/deploy/App.html) to find the file and copy it into the custom HTML app.

### Using the App

Features of the Story Board app include:

* Displays user stories, defects, and defect suites in the iteration
* Create and add new user stories to the board
* Drag-and-drop a card between columns to quickly change the state of a story
* Drag-and-drop a story within the same column to change rank
* Direct links to stories and defects
* Edit work items without leaving the board
* Print functionality

[View a screencast demo of the app](http://screencast.com/t/YQAogqoluR) to see how it works.

## Customize this App

You're free to customize this app to your liking (see the License section for details). If you need to add any new Javascript or CSS files, make sure to update config.json so it will be included the next time you build the app.

This app uses the Rally SDK 2.0 Preview. The documentation for the latest preview can be found [here](http://developer.rallydev.com/apps/2.0p5/doc/). 

Available Rakefile tasks are:

    rake build                      # Build a deployable app which includes all JavaScript and CSS resources inline
    rake clean                      # Clean all generated output
    rake debug                      # Build a debug version of the app, useful for local development
    rake deploy                     # Deploy an app to a Rally server
    rake deploy:debug               # Deploy a debug app to a Rally server
    rake deploy:info                # Display deploy information
    rake jslint                     # Run jslint on all JavaScript files used by this app, can be enabled by setting ENABLE_JSLINT=true.

## License

StoryBoard is released under the MIT license. See the file [LICENSE](https://raw.github.com/RallyApps/StoryBoard/master/LICENSE) for the full text.
