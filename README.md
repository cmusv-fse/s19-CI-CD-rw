Continuous Integration [![CircleCI](https://circleci.com/gh/cmusv-fse/s19-CI-CD.svg?style=svg&circle-token=0bfe9b7c8d7b3ab9399690cc3d1bd0b9231243f4)]
==============
Implementation of a bowling score card.

Reference for Unit Testing lab for FSE Fall 2015 at CMU-SV.

Updated for CircleCI Integration for FSE Spring 2018 at CMU-SV.

Updated for CI/CD recitation for FSE Spring 2019 at CMU-SV.


Install
==============
1. Install needed tools using: `npm install -g grunt-cli mocha istanbul`
2. Install needed dependencies using: `npm install`

Tests results
==============
* `grunt test`

Coverage results
==============
* Option 1 
* `grunt coverage`

* Option 2
* `nyc grunt test`

* The results with be in `coverage/lcov-report/index.html`
![Alt text](/resources/coverage.jpg)

CircleCI integration
==============

* Link your account with CircleCI by following 
["Getting Started with CircleCI"](https://circleci.com/docs/2.0/getting-started/#section=getting-started).


* After the account is linked, when you push changes to the repo CircleCI will run your tests and code coverage.

* You can see the results under `Test Summary` and `Artifacts > Coverage`.

### Test Summary
![Alt text](/resources/TestSummary.png)

### Artifacts > Coverage
![Alt text](/resources/Artifacts.png)

