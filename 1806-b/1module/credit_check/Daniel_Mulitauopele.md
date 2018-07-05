Assessor: Sal

Repo: https://github.com/DanielMulitauopele/credit_check_project/

## Functionality: 4

Notes:

Like that you tackled AmEx!

- [x] Student completes through Iteration 3

## Mechanics: 3

Notes:

* Looks good!

The student(s):

- [x] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [x] implements best-choice enumerable methods to iterate over collections
- [x] uses boolean expressions and flow control structures to logically manage a program's flow
- [x] uses methods, arguments, and return values to break code into logical components
- [x] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design: 3

Notes:

* *Main comment on the project:* It looks like you're overusing instance variables. Reserve these variables for things that you would actually consider as the *state* of the object. Replace the pattern that youused with methods that *take arguments* and *return values*, then use those return values as arguments for the next method that you'd like to call.
* Be sure to remove the comments from the file once you've gotten your code where you want it to be. Generally Ruby code should be self-documenting (it should read enough like English that it should be clear to me what's happening without a comment - make that your goal).
* Otherwise looks good!

The student(s):

- [x] adheres to the Single Responsibility and DRY principles
- [x] creates Objects and Classes that appropriately encompass state and behavior
- [ ] uses instance and local variables appropriately
- [x] writes readable code with the following characteristics:
    * Variable and method names are self explanatory
    * Methods are under 7 lines
    * Lines of code are under 80 characters
    * Project directory structure adheres to convention
    * A linter reports less than 5 errors

## Testing: 2

Notes:

* At this point would like to see tests for your supporting methods as well as your high level interface.
* I can absolutely see an argument for only testing your interface (those meethods you actually expect to use from outside the class), but if you're going to go down this path then your other methdos should be private.
* While I can see that argument in this case, in general we find that M1 students under test, rather than over test. At this point would err on the side of creating more tests.

The student(s):

- [x] writes Minitest tests that describe the expected behavior of a program according to technical specifications
- [x] names and orders tests so that a test file reads like documentation
- [x] writes Minitest assertions that accurately test a piece of functionality
- [ ] writes both integration and unit tests

## Version Control: 3

* Looks like you have a version of this project that is in a class and one htat is not. Go ahead and trust your version control! If you commit a version with the algorithm working outside of a class, then you should feel free to delete it when you start to move things to a class.
* Really like all the commits you're making!
* Could potentially have more than one pull request. Generally, when you're making changes aim to do that out on a branch. Make a separate branch for each piece of functionality.

Notes:

The student(s):

- [x] hosts their code on the master branch of their remote repository
- [x] makes commits in small chunks of functionality
- [x] submits and merges Pull Requests using the Github interface
