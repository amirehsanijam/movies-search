# This is the the movie db iOS application

## Git Policy:
This repository is based on Git Flow, meaning that the master branch always represents the production(public) version of the application. The develop branch is the main development branch and all the feature branches should be spinned off from the branch and merge to it eventually. Each new feature should be implemented under a new feature/<feature name> branch, and when finished, be merged back to the develop branch.

## Features:
* Item 1 Search: Users can search the movies
* Item 2 Movie Detail: Shows the movies detail

## Libraries:
This project uses COCOAPODS for third party libraries management.
* Item 1 Resolver: A library to handle all the dependency injections 

## Development:
This application originally is implemented using Xcode 13.4
The api doesn't work with IPs from Iran. Should use VPN in order to work with the app.


## How to setup project:
Open terminal and navigate to the directory you want to clone the project and run command below:
```
gite clone git@github.com:amirehsanijam/movies-search.git
``` 
When the clone is compeleted, use line below to install pods. Make sure the COCOAPODS is installed on your device. COCOAPODS installation guide is available in [here](https://guides.cocoapods.org/using/getting-started.html). If you already installed it on your device then run the command below.
```
pod install
```
When the pod installed all libraries, navigate to the cloned project directory and open `FilimoTMDB.xcworkspace` file to the project in XCode.

## How to run tests:
All test cases have written based on a stub set on the project. Should follow the following steps to prepare the the app for running tests:
* Open the workspace from the project directory (Should open Xcode)
* To run all the tests need to run the project under tests (CMD + U)
You can find the tests source files under `FilimoTMDBTests` and `FilimoTMDBUITests` group in the Xcode files navigator.

* To run a single test hit the diamond button next to the test name. If run suceed, the `Succeed`  is shown. Otherwise failure message is shown on the screen.

