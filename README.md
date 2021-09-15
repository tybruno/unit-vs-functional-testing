# unit-vs-functional-testing

We discuss the differences between Unit and Functional testing with Python examples. We also make a case of why functional testing should be the minimum requirement for testing a project.

## TLDR
#### What is Unit Testing?

[A unit test is a way of testing a unit - the smallest piece of code that can be logically isolated in a system.](https://smartbear.com/learn/automated-testing/what-is-unit-testing/)

Since unittest is designed to test only the individual unit (i.e. function/method), other function defined in the individual unit will need to be [Mocked](https://docs.python.org/3/library/unittest.mock.html) out.

#### What is Functional Testing?

Since functional tests are designed to test your code in it's entirety, you will only mock out external apps / resources.
#### Why Use Functional Testing over Unit Testing?

- *simplicity*: writing functional tests are simple and quick since it only requires mocking out external apps / resources / libraries.
- *efficiant*: Since we are able to test multiple written functions with a single test it will be able to cover more code.

## Requirements
This project requires [jupyter-lab](https://jupyter.org/install.html) to be installed.

## Installation
`git clone https://github.com/tybruno/unit-vs-functional-testing.git`

`jupyter-lab`
