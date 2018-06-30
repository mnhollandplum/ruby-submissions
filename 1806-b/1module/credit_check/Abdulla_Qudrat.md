Assessor: Sal

Repo: https://github.com/abdyqew/credit_check/

## Functionality: 4

Notes: Like that this works for AmEx! Good job here!

- [x] Student completes through Iteration 3

## Mechanics: 3

Notes:

Lots of good stuff going on here.

* Really like the `valid_number?` method and the way it uses other supporting methods.
* Logic of the methods each seems clear.

Things to work on:

* When naming variables, go ahead and use the extra characters instead of abbreviating.
* Like that you're using pseudocode, but remove the comments once you've written the code.
* Try to keep your procedural code separate from your OO code: Instead of putting `credit_check = CreditCheck.new` at the bottom of this file, put it in a separate file and then load the `CreditCheck` class into that file using `require './lib/credit_check'`.
* Duplication in `valid_number?` and `validation_output`. Use `valid_number?` inside `validation_output` to clean up.

```ruby
def validation_output(card_number)
  if valid_number?(card_number)
    "The number #{card_number} is valid"
  else
    "The number #{card_number} is invalid"
  end
end
```

The student(s):

- [x] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [x] implements best-choice enumerable methods to iterate over collections
- [x] uses boolean expressions and flow control structures to logically manage a program's flow
- [x] uses methods, arguments, and return values to break code into logical components
- [x] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design: 3

Notes:

* Also lots of good stuff going on here. Be sure to create a `lib` and `test` directory.

The student(s):

- [x] adheres to the Single Responsibility and DRY principles
- [x] creates Objects and Classes that appropriately encompass state and behavior
- [x] uses instance and local variables appropriately
- [ ] writes readable code with the following characteristics:
    * Variable and method names are self explanatory
    * Methods are under 7 lines
    * Lines of code are under 80 characters
    * Project directory structure adheres to convention
    * A linter reports less than 5 errors

## Testing: 3

Notes:

* Looks good!

The student(s):

- [x] writes Minitest tests that describe the expected behavior of a program according to technical specifications
- [x] names and orders tests so that a test file reads like documentation
- [x] writes Minitest assertions that accurately test a piece of functionality
- [x] writes both integration and unit tests

## Version Control: 3

Notes:

The student(s):

- [x] hosts their code on the master branch of their remote repository
- [x] makes commits in small chunks of functionality
- [x] submits and merges Pull Requests using the Github interface
