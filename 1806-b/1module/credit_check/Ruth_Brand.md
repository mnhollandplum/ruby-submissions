Assessor: Megan McMahon

Repo: https://github.com/worldwideruth/credit_check.rb/blob/master/cc_class_assign.rb

## Functionality: 2

Notes:

* The algorithm and Class look GREAT!

- [ ] Student completes through Iteration 3

## Mechanics: 3

Notes:

* I like the idea of setting up instance variables in the first method so that you are not passing around arguments all over the place - I would just be careful of how many instance variables get created.
* There should not be executable code in your class file outside of the class itself (see lines 80 - 83 in cc_class_assign.rb)

The student(s):

- [x] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [x] implements best-choice enumerable methods to iterate over collections
- [x] uses boolean expressions and flow control structures to logically manage a program's flow
- [x] uses methods, arguments, and return values to break code into logical components
- [x] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design: 3

Notes:

* Overall, the design looks really good.
* Keep an eye on how you are naming things, a name that makes sense today when you are deep in the weeds of the program may not make sense a month from now when you are reviewing your code!
* In terms of class structure, the convention is to have all the methods inside of the class indented two spaces, rather than lined up directly underneath the class name.  For example:

``` ruby
class Dog
  def bark
    p "Woof"
  end
end
```


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

## Testing: 1

Notes:

The student(s):

- [ ] writes Minitest tests that describe the expected behavior of a program according to technical specifications
- [ ] names and orders tests so that a test file reads like documentation
- [ ] writes Minitest assertions that accurately test a piece of functionality
- [ ] writes a test before writing code that implements the behavior to make that test pass
- [ ] writes both integration and unit tests

## Version Control: 2

Notes:

* Try to make smaller, more frequent commits.
* For the next project, really dig in to branching and pull requests.

The student(s):

- [x] hosts their code on the master branch of their remote repository
- [ ] makes commits in small chunks of functionality
- [ ] submits and merges Pull Requests using the Github interface
