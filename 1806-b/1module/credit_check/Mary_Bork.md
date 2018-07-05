Assessor:

Repo:

There's some stylistic issues that need to be cleaned up, and we would like to see it put into a class. Overall, the algorithm looks really good!

## Functionality: 1

Notes:

- [ ] Student completes through Iteration 3

## Mechanics: 2

Notes:

* Instead of shoveling an if statement, make the shoveling part of the individual branches i.e.

```ruby
if num >= 10
   singles_array << num - 9
else
   singles_array << num
end
```

instead of

```ruby
	SinglesArray << if num >= 10
              			num - 9
                	else
                			num
                	end
```



The student(s):

- [x] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [x] implements best-choice enumerable methods to iterate over collections
- [x] uses boolean expressions and flow control structures to logically manage a program's flow
- [ ] uses methods, arguments, and return values to break code into logical components
- [ ] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design: 2

Notes:

* Variables should be named lowercase with underscores (snake case)
* Indentation should be consistent
* Indentation should be two characters

The student(s):

- [ ] adheres to the Single Responsibility and DRY principles
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

The student(s):

- [ ] writes Minitest tests that describe the expected behavior of a program according to technical specifications
- [ ] names and orders tests so that a test file reads like documentation
- [ ] writes Minitest assertions that accurately test a piece of functionality
- [ ] writes a test before writing code that implements the behavior to make that test pass
- [ ] writes both integration and unit tests

## Version Control: 3

Notes:

Really great use of PRs!

The student(s):

- [x] hosts their code on the master branch of their remote repository
- [x] makes commits in small chunks of functionality
- [x] submits and merges Pull Requests using the Github interface
