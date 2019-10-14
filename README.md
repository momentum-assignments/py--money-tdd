# TDD and Money

## Description

Using a set of provided class skeletons, create Currency and Money classes that pass all tests.

## Objects

After completing this assignment, you should understand:

- How classes define methods for their objects

After completing this assignment, you should be able to:

- Create an instance method
- Call instance methods

## Details

### Deliverables

- A Git repo containing all the provided starter files completed to make this program work.

### Requirements

- Tests in `money_test.py` pass
- No PEP8 or Pyflakes warnings or errors

### Step 1

Read the classes `Currency` and `Money` as well as their tests. Using the docstrings included, complete these classes. Upon completion, the tests in `money_test.py` should pass.

To run the tests, make sure you have run `pipenv install` and `pipenv shell` and then run `pytest -x`.

### Step 2

Take a look at [this guide to Python's magic methods](https://rszalski.github.io/magicmethods/). Write tests for using the standard mathematical operators (`+`, `-`, `*`, `/`) on `Money` and then implement the methods needed. To write these tests, look at the existing tests and modify them.

