Assessor: Megan McMahon

Repo: https://github.com/SKG360/skg_git_project

## Functionality: 1

Notes:

I really like how you have the different pieces of the algorithm broken up into different methods - this is the kind of thing we like to see.  Unfortunately, I was not able to run the algorithm. It looks like there needs to be some clean up of method names and arguments to make this work.

- [ ] Student completes through Iteration 3

## Mechanics: 2

Notes:

There are a lot of good mechanics here, but just a few things to think about - Really be careful about when you are using instance variables when you could be using local variables.  Also, make sure all of your methods are named (and named appropriately), and if they should take an argument.  For example, your method `validnumber?` should take an argument that is the credit card number and, based on the project spec, it should be named `valid_number?`.

The student(s):

- [x] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [x] implements best-choice enumerable methods to iterate over collections
- [x] uses boolean expressions and flow control structures to logically manage a program's flow
- [ ] uses methods, arguments, and return values to break code into logical components
- [ ] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design: 1

Notes:

You should not include any executable code at the bottom of your CreditCheck class (lines 126 - 136).  Also, comments in your code that explain what a method does can be helpful, but having commented out code that you are no longer using, makes it very difficult to read.  It does look like you have a good grasp on methods having single responsibility, and that is great!

The student(s):

- [x] adheres to the Single Responsibility and DRY principles
- [ ] creates Objects and Classes that appropriately encompass state and behavior
- [ ] uses instance and local variables appropriately
- [ ] writes readable code with the following characteristics:
    * Variable and method names are self explanatory
    * Methods are under 7 lines
    * Lines of code are under 80 characters
    * Project directory structure adheres to convention
    * A linter reports less than 5 errors

## Testing: 1

Notes:

This looks like a great start, all the mechanics of the test look good, but I am concerned that it doesn't run because of syntax errors in your Class_Credit_Check file.  Also, we would like to see tests for each of your methods, as well as tests that run the whole program.

The student(s):

- [ ] writes Minitest tests that describe the expected behavior of a program according to technical specifications
- [ ] names and orders tests so that a test file reads like documentation
- [ ] writes Minitest assertions that accurately test a piece of functionality
- [ ] writes a test before writing code that implements the behavior to make that test pass
- [ ] writes both integration and unit tests

## Version Control: 2

Notes:

I like the commit history and that you have multiple pull requests - that is great!  I would have liked to see the testing branch merged into master.

The student(s):

- [ ] hosts their code on the master branch of their remote repository
- [x] makes commits in small chunks of functionality
- [x] submits and merges Pull Requests using the Github interface
