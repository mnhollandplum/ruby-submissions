Assessor: Brian

Repo: https://github.com/izcom/mastermind

Notes:

* Colors should be stored in an array, not a hash
* I like the use of helper methods in the start method. Play should be a helper method
* Play method is too long
* "p".downcase will just be "p". downcase should be called on the user's input
* Bug when using = instead of ==
* Lots of unnecessary to_s and gsub
* Cheat will never work because the guess is formatted as an array of characters
* Should be using a block parameter to track index, not a counter
* Enumerables are preferred over counters and loops

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
- [ ] Ruby methods used are logical and readable
- [x] Code is indented properly
- [x] Code does not exceed 80 characters per line
- [x] Each class has correctly-named files and corresponding test files in the proper directories

### 2. Breaking Logic into Components: 2

- [ ] Code is effectively broken into methods & classes
- [ ] Developer writes methods less than 10 lines
- [ ] No more than 3 methods break the principle of SRP


### 3. Test-Driven Development: 2

- [ ] Each method is tested  
- [ ] Tests implement Ruby syntax & style   


### 4. Functionality: 3

- [x] Application meets all requirements (extension not req'd)
