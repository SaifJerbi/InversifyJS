# Contributing to Inversify

## Setup

1 - Clone your fork of the repository:
```
$ git clone https://github.com/YOUR_USERNAME/InversifyJS.git
```
2 - Install npm dependencies:
```
$ npm install
```
3 - Install TSD typings:
```
$ tsd install
```

4 - Run tests:
```
$ gulp test
```

## Guidelines

Please try to [combine multiple commits before pushing](http://stackoverflow.com/questions/6934752/combining-multiple-commits-before-pushing-in-git)

Please use `TDD` when fixing bugs. This means that you should write a unit test that fails because 
it reproduces the issue, then fix the issue finaly run the test to ensure that the issue has been 
resolved. This helps us to prevent fixed bugs from happening again in the future.

Please try keep the test coverage at 100%. Write additional unit test if necesary