# Project Title

Appium testing for the Google Music Player example project

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

1 [Node](https://nodejs.org/en/)
2 [NPM](https://www.npmjs.com/)
3 [Android Emulator](https://developer.android.com/studio/run/emulator)
4 [Git]()


### Installing

A step by step series of examples that tell you have to get a development env running

Download project from github.

```
git clone https://github.com/menziwac/appiumtests.git
```

change to the directory of the project

```
cd appiumtests
```

Install dependencies

```
npm install
```

run tests

```
npm test
```



## expected results

```
 Test Playing a song via genre
    Test click genres
      √ test-click-genres (2394ms)
      √ test-click-rock-genre (1139ms)
      √ test-click-song-awakening (1263ms)
Text from the player bar:  Awakening
      √ should-have-awakening-on-play-bar (162ms)
```
## Built With

* [Mocha](https://mochajs.org/) - Javascript testing framework
* [Chai](http://www.chaijs.com/) -TDD assertion library
* [Webdriverio](http://webdriver.io/) - Webdriver bindings for node js

## Authors

* **Chuma Menziwa** - *Initial work* - [PurpleBooth](https://github.com/menziwac)

See also the list of [contributors](https://github.com/menziwac/appiumtests/contributors) who participated in this project.
