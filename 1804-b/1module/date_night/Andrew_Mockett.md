Assessor: Brian

Repo: https://github.com/MacInnes/date_night

Notes:

* No need to assert_equal and refute_equal
* Use nil to represent emptiness, or an empty placeholder, instead of values like 0, or a new Node with no values
* Use assertions to make sure your tree structure is correct, not just that the depth is returned
* Good example of edge case testing, depth_of node that doesn't exist
* Try to name your variables more specifically, i.e. don't call a block variable 'each'

## Evaluation Rubric

The project will be assessed with the following guidelines:

* 4: Above expectations
* 3: Meets expectations
* 2: Below expectations
* 1: Well-below expectations

**Expectations:**

### 1. Ruby Syntax & Style: 2

- [ ] Applies appropriate attribute encapsulation  
- [ ] Developer creates instance and local variables appropriately
- [ ] Naming follows convention (is idiomatic)
- [ ] Ruby methods used are logical and readable
- [ ] Code is indented properly
- [ ] Code does not exceed 80 characters per line
- [ ] Each class has correctly-named files and corresponding test files in the proper directories

### 2. Breaking Logic into Components: 3

- [ ] Code is effectively broken into methods & classes 
- [ ] Developer writes methods less than 10 lines 
- [ ] No more than 3 methods break the principle of SRP 


### 3. Test-Driven Development: 3 

- [ ] Each method is tested  
- [ ] Tests implement Ruby syntax & style  
- [ ] Tests exist to cover edge cases
- [ ] Tests covers critical functionality of software
- [ ] Testing exhibits TDD approach
- [ ] Test coverage is measured with [SimpleCov](https://github.com/colszowka/simplecov)
- [ ] Test coverage exceeds 95%

### 4. Version Control: 3

Expectations:

- [ ] Developer commits at a pace of at least 1 commit per hour
- [ ] Developer implements branching and PRs
- [ ] The final submitted version is merged into master

### 5. Functionality: 2

- [ ] Application meets all requirements (extension not req'd)
