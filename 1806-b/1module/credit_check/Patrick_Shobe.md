Assessor: Brian 

Repo: https://github.com/patrickshobe/Luhn-Algorithm

## Functionality: 4

Notes:

* Great job!

- [x] Student completes through Iteration 3

## Mechanics: 3

Notes:

* In your test file, require_relative './credit_check' doesn't work because the credit_check file is not in the test directory. This require statement should be require './lib/credit_check'. We always run our tests from the root directory with `ruby test/name_of_test_file.rb`. 


The student(s):

- [x] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [x] implements best-choice enumerable methods to iterate over collections
- [x] uses boolean expressions and flow control structures to logically manage a program's flow
- [x] uses methods, arguments, and return values to break code into logical components
- [x] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design: 3

Notes:
* In general, your naming could be improved. There are a lot of variables named array. Try to be more specific about what you expect that array to be. Your method names aren't very descriptive either. For instance, someone reading your code will not immediately know what the doubler or reducer methods are supposed to do. 
* There are some lines of code that should be broken up for readability. For instance, the line 

```ruby
array[index] = array[index].to_s.chars.map(&:to_i).sum if array[index] > 9
```

could be written as

```ruby
if array[index] > 9
   digits = array[index].to_s.chars.map(&:to_i)
   array[index] = digits.sum
end
```

Sometimes single line syntax can be more confusing, even if Rubocop tells you otherwise.
* I like that you used a class to create your runner file. It makes a nice and neat package for the code

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

* Instead of `assert_equal 'CreditCheck', credit_check.class.to_s`, use `assert_instance_of CreditCheck, credit_check`
* Test all of your methods. For example, you have functionality for the doubler method to handle arrays with and without the check digit. Test both of those paths, as well as the helper methods doubler_check and doubler_no_check. This would be unit AND integration testing

The student(s):

- [x] writes Minitest tests that describe the expected behavior of a program according to technical specifications
- [x] names and orders tests so that a test file reads like documentation
- [x] writes Minitest assertions that accurately test a piece of functionality
- [ ] writes both integration and unit tests

## Version Control: 3

Notes:

The student(s):

- [x] hosts their code on the master branch of their remote repository
- [x] makes commits in small chunks of functionality
- [x] submits and merges Pull Requests using the Github interface
