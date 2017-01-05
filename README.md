# Debugging practice

You can use this exercise to practice and assess your debugging skill.

Take a couple of minutes to read this README thoroughly before you start.

## Instructions

The goal is to get all the tests in the `spec/` directory passing.

**You can assume the tests are correct and do not need to be changed.** (You can add your own extra tests to help you debug, if you like.

1. Fork this repo.

2. Clone your fork to your machine.

3. Install the dependencies by running `bundle` in the root of the repo.

4. Run the tests by running `rspec` in the root of the repo.

5. Get all the tests in `spec/` passing.

6. To check that your debugged code will be assessed as correctly debugged by Travis, run `rake verify`.  This runs a clean version of the tests.  If all these tests pass, you've successfully debugged the repo.

7. Make a pull request to this repo to submit your solution.

## Notes

* Don't change the files in the `.spec_verify/` directory.

## Run the project

If you need to run the project, start IRB and type in:

```ruby
require_relative("./lib/blackjack/command_line_interface")

CommandLineInterface.new(STDIN, STDOUT, Game.new)
```
