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

- [x] Applies appropriate attribute encapsulation  
- [x] Developer creates instance and local variables appropriately
- [ ] Naming follows convention (is idiomatic)
- [x] Ruby methods used are logical and readable
- [x] Code is indented properly
- [x] Code does not exceed 80 characters per line
- [x] Each class has correctly-named files and corresponding test files in the proper directories

### 2. Breaking Logic into Components: 3

- [x] Code is effectively broken into methods & classes 
- [x] Developer writes methods less than 10 lines 
- [x] No more than 3 methods break the principle of SRP 


### 3. Test-Driven Development: 3 

- [x] Each method is tested  
- [x] Tests implement Ruby syntax & style  
- [x] Tests exist to cover edge cases
- [x] Tests covers critical functionality of software
- [x] Testing exhibits TDD approach

### 4. Version Control: 3

Expectations:

- [x] Developer commits at a pace of at least 1 commit per hour
- [x] Developer implements branching and PRs
- [x] The final submitted version is merged into master

### 5. Functionality: 2

- [ ] Application meets all requirements (extension not req'd)
