Assessor: Sal

Repo: https://github.com/bghalami/credit_check/

## Functionality: 4

Notes:

Good job tackling the extensions!

- [x] Student completes through Iteration 3

## Mechanics: 3

Notes:

Generally looks good!

The student(s):

- [x] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [x] implements best-choice enumerable methods to iterate over collections
- [x] uses boolean expressions and flow control structures to logically manage a program's flow
- [x] uses methods, arguments, and return values to break code into logical components
- [x] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design: 2

Notes:

Two quick notes:

* Main comment *on the entire project*: You've used instance variables to hold state instead of using return values from methods. This ends up meaning that your instance variables become kind of a dumping ground. They should be reserved for only those things that really represent the *state* of an object, and not just a convenient way to access information between methods. Instead use return values and arguments to get information from one method into the next.
* The command line interface feels to me like fundamentally a separate responsibility from checking whether the card is valid or not. Would ideally like to see that in a separate class.

The student(s):

- [ ] adheres to the Single Responsibility and DRY principles
- [x] creates Objects and Classes that appropriately encompass state and behavior
- [ ] uses instance and local variables appropriately
- [x] writes readable code with the following characteristics:
    * Variable and method names are self explanatory
    * Methods are under 7 lines
    * Lines of code are under 80 characters
    * Project directory structure adheres to convention
    * A linter reports less than 5 errors

## Testing: 3

Notes:

Tests look good!

The student(s):

- [x] writes Minitest tests that describe the expected behavior of a program according to technical specifications
- [x] names and orders tests so that a test file reads like documentation
- [x] writes Minitest assertions that accurately test a piece of functionality
- [x] writes both integration and unit tests

## Version Control: 3

Notes:

Love this! Good job with all the commits. Could potentially have more pull requests (e.g. work on branches that implement smaller pieces of functionality), but can see how that would be hard on this particular project.

The student(s):

- [x] hosts their code on the master branch of their remote repository
- [x] makes commits in small chunks of functionality
- [x] submits and merges Pull Requests using the Github interface
