# MongoDB Cookbook

This is a cookbook for MongoDB, using Chef (configuration management tool).

## Tests

- ChefSpec runs unit tests. This is done using the RSpec syntax.

- InSpec runs integration test (also done using the RSpec syntax).

## About the tests

-  add the MongoDB repository to the sources list
-  install MongoDB v3.*
  - Is it correctly installed?
- is MongoDB added to source list using the its repo?
- Is the package list updated?
-  conduct integration tests to ensure that software has installed correctly.
  Including tests for:
  - Is MongoDB installed?
  - Is the version of MongoDB >= v3.*


-  conduct unit tests to ensure that code is robust and there is no error in it.
