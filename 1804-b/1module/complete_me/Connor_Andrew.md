Assessor: Brian

Repo: https://github.com/letsdothis64/complete_me

Notes:

* Any time you're saying if ..., then return a boolean, there's an opportunity for a refactor

## Evaluation Rubric

The project will be assessed with the following guidelines:

* 4: Above expectations
* 3: Meets expectations
* 2: Below expectations
* 1: Well-below expectations

**Expectations:**

### 1. Ruby Syntax & Style: 2

* Should use underscore for naming test files, not hyphen
* Should have spacing inbetween an assignment

- [x] Applies appropriate attribute encapsulation  
- [x] Developer creates instance and local variables appropriately
- [ ] Naming follows convention (is idiomatic)
- [x] Ruby methods used are logical and readable  
- [x] Developer implements appropriate enumerable methods (#each is used only when necessary)
- [ ] Code is indented properly
- [x] Code does not exceed 80 characters per line
- [ ] Each class has correctly-named files and corresponding test files in the proper directories
- [x] Code has been linted and corrected properly.

- [x] 2: Below expectations

### 2. Breaking Logic into Components: 3

- [x] Code is effectively broken into methods & classes
- [x] Developer writes methods less than 8 lines
- [x] Methods do not break the principle of SRP

- [x] 3: Meets expectations

### 3. Test-Driven Development: 2

* Node testing is not complete. It should be testing the other attributes like weight and child_nodes
* It would be nice if test_populate was separated in to two tests, one with the whole dictionary and one without
* Instead of first_hash second_hash in test_weight, I would've just had one variable called expected
* Tests could benefit from a setup method
* In test_select, I would have made sure that the usage weighting doesn't apply to substrings that haven't been selected

- [ ] Each method is tested  
- [ ] Functionality is accurately covered
- [ ] Tests implement Ruby syntax & style   
- [x] Balances unit and integration tests
- [x] Evidence of edge cases testing
- [ ] Test Coverage metrics are present (SimpleCov)
- [ ] Test Coverage metrics exceed 95%

- [x] 2: Below expectations


### 4. Git Workflow: 3

- [x] Repository demonstrates that each member of team has contributed fairly equally.
- [x] Developers commit at a rate of approximately one commit every 30 minutes.
- [x] Repository shows the use of branches.
- [x] Developers use a pull request workflow.
- [x] Developers resolve HoundCI complaints in their pull requests.

- [x] 3: Meets expectations

### 5. Functionality: 4

- [x] Application meets all requirements (extensions not required for a 3)
- [x] Application passes the spec harness

- [x] 4: Above expectations
