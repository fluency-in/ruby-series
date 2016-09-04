# Ruby: Series

Write a program that will take a string of digits and give you all the contiguous substrings of length `n` in that string.

For example, the string "49142" has the following 3-digit series:

- 491
- 914
- 142

And the following 4-digit series:

- 4914
- 9142

And if you ask for a 6-digit series from a 5-digit string, you deserve
whatever you get.

Note that these series are only required to occupy *adjacent positions*
in the input; the digits need not be *numerically consecutive*.

The tests use the Minitest testing framework. To install it run the command:

    gem install minitest

Run the tests with the `ruby` command:

    ruby series_test.rb

## Resources

If you have never used Minitest, check out [Intro to TDD][tdd] tutorial from Jumpstart Lab.

[tdd]: http://tutorials.jumpstartlab.com/topics/testing/intro-to-tdd.html

## Source

A subset of the Problem 8 at Project Euler [http://projecteuler.net/problem=8](http://projecteuler.net/problem=8)

This exercise is from the [Ruby][ruby] track on [Exercism][exercism]

[exercism]: http://exercism.io
[ruby]: http://exercism.io/languages/ruby



