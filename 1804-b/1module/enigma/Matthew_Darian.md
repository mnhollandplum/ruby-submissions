Assessor: Brian

Repo: https://github.com/wehttamclan/enigma/

Notes:

* Don't add commits after the deadline
* Don't push breaking code into master
* Shouldn't hard code tests to only work with today's date
* You are ignoring the optional date variable passed to encrypt and decrypt methods
* Don't have @characters and @char_map. If an IVar can be easily calculated, it doesn't need to be an instance variable

## Evaluation Rubric

The project will be assessed with the following guidelines:

* 4: Above expectations
* 3: Meets expectations
* 2: Below expectations
* 1: Well-below expectations

**Expectations:**

### 1. Ruby Syntax & Style: 1

- [ ] Applies appropriate attribute encapsulation  
- [ ] Developer creates instance and local variables appropriately
- [x] Naming follows convention (is idiomatic)
- [ ] Ruby methods used are logical and readable  
- [ ] Developer implements appropriate enumerable methods (#each is used only when necessary)
- [x] Code is indented properly
- [x] Code does not exceed 80 characters per line
- [x] Each class has correctly-named files and corresponding test files in the proper directories
- [x] Code has been linted and corrected properly.

### 2. Breaking Logic into Components: 3

- [x] Code is effectively broken into methods & classes
- [x] Developer writes methods less than 8 lines
- [x] Methods do not break the principle of SRP

### 3. Test-Driven Development: 1

- [ ] Each method is tested  
- [ ] Functionality is accurately covered
- [ ] Tests implement Ruby syntax & style   
- [ ] Balances unit and integration tests
- [ ] Evidence of edge cases testing
- [ ] Test Coverage metrics are present (SimpleCov)
- [ ] Test Coverage metrics exceed 95%

### 4. Git Workflow: 2

- [x] Repository demonstrates that each member of team has contributed fairly equally.
- [x] Developers commit at a rate of approximately one commit every 30 minutes.
- [x] Repository shows the use of branches.
- [x] Developers use a pull request workflow.
- [ ] Developers resolve HoundCI complaints in their pull requests.

### 5. Functionality: 1

- [ ] Application meets all requirements (extensions not required for a 3)

