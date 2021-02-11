# JavaScript Koans

This repo contains several failing tests, which can be seen by opening ```KoansRunner.html``` in a browser. The test files live in ```/koans```. This is a hands-on re-introduction to JavaScript syntax, and an opportunity to work within a test suite. The Koans use [Jasmine](https://jasmine.github.io/1.3/introduction.html), a popular alternative which is largely interchangeable with [Mocha](https://mochajs.org/). The testing suites are included within the repo.

## Installation
[Pomander](https://github.com/hackreactor/precourse-pomander) will check the code for syntax errors and violations against the style guide before each commit. It uses a pre-commit hook to run staged files through ```eslint``` before each commit. ```eslint``` is a linter that will block commits should there be any syntax errors, or, should the style guide be violated. There are some preferred whitespace style rules that will give warnings but not block commits.

The following command is run from within the repository to install Pomander:

```curl -s https://raw.githubusercontent.com/hackreactor/precourse-pomander/master/bin/install | bash```

## Minimum Requirements
Tests files to pass:
  - [x] AboutExpects.js
  - [x] AboutArrays.js
  - [x] AboutFunctions.js
  - [x] AboutObjects.js
