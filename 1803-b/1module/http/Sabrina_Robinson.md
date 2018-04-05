Assessor: Brian 

Repo: https://github.com/shebesabrina/HTTP-Yeah-You-Know-Me

Notes:

* Unit tests don't need Faraday
* Each method should be tested
* Don't need to use self. to use methods within the same class
* Using a hash would have made this readable
* Executable code i.e. server.run_server should be in a separate runner file

## Evaluation Rubric

The project will be assessed with the following guidelines:

* 4: Above expectations
* 3: Meets expectations
* 2: Below expectations
* 1: Well-below expectations

### 1. Ruby Syntax & Style: 3

Expectations:

- [x] Applies appropriate attribute encapsulation  
- [x] Developer creates instance and local variables appropriately
- [x] Naming follows convention (is idiomatic)
- [x] Ruby methods used are logical and readable  
- [x] Developer implements best-choice enumerable methods
- [x] Code is indented properly
- [x] Code does not exceed 80 characters per line
- [x] A directory/file structure provides basic organization via lib/ and/or /test


### 2. Breaking Logic into Components: 3

Expectations:

- [x] Code is effectively broken into methods & classes
- [x] Developer writes methods less than 7 lines
- [x] No more than 3 methods break the principle of SRP

### 3. Test-Driven Development: 2

Expectations:

- [ ] Each method is tested  
- [ ] Functionality is accurately covered
- [ ] Tests implement Ruby syntax & style   
- [ ] Balances unit and integration tests
- [ ] Evidence of edge cases testing
- [ ] Test Coverage metrics are present (SimpleCov)
- [x] A test RakeTask is implemented

### 4. Functionality: 2

Expectations:

- [ ] Developer completes through iteration 4

### 5. Version Control: 3

- [x] Developer commits at a pace of at least 1 commit per hour
- [x] Developer implements branching and PRs
- [x] The final submitted version is merged into master
