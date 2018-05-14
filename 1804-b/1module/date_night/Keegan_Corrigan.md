Assessor: Brian 

Repo: https://github.com/KeeganCorrigan/date_night_1804_Keegan_Corrigan

Notes: 

* gitignore your coverage folder
* Node tests don't cover functionality of this class
* explicitly set your children to nil, don't call their attr_readers
* Be as specific as possible with your tests, i.e. use assert_equal over assert_instance_of
* Some redundant tests
* Good edge case testing with depth if the node isn't in the tree
* Opportunities for refactoring, especially in insert

## Evaluation Rubric

The project will be assessed with the following guidelines:

* 4: Above expectations
* 3: Meets expectations
* 2: Below expectations
* 1: Well-below expectations

**Expectations:**

### 1. Ruby Syntax & Style: 3

- [x] Applies appropriate attribute encapsulation  
- [x] Developer creates instance and local variables appropriately
- [x] Naming follows convention (is idiomatic)
- [x] Ruby methods used are logical and readable
- [x] Code is indented properly
- [x] Code does not exceed 80 characters per line
- [x] Each class has correctly-named files and corresponding test files in the proper directories

### 2. Breaking Logic into Components: 2

- [ ] Code is effectively broken into methods & classes 
- [ ] Developer writes methods less than 10 lines 
- [x] No more than 3 methods break the principle of SRP 


### 3. Test-Driven Development: 2

- [ ] Each method is tested  
- [x] Tests implement Ruby syntax & style  
- [x] Tests exist to cover edge cases
- [x] Tests covers critical functionality of software
- [x] Testing exhibits TDD approach
- [x] Test coverage is measured with [SimpleCov](https://github.com/colszowka/simplecov)
- [x] Test coverage exceeds 95%

### 4. Version Control 3

Expectations:

- [x] Developer commits at a pace of at least 1 commit per hour
- [x] Developer implements branching and PRs
- [x] The final submitted version is merged into master

### 5. Functionality: 2

- [x] Application meets all requirements (extension not req'd)
