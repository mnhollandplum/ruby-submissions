## Rubric

### Evaluator: Ian Douglas

### GitHub Repo: https://github.com/zdcthomas/job-tracker

### Notes:

- incomplete dashboard, jobs page with sorting/filtering
- very heavy logic happening in controllers
- no model-level methods at all
- missing links on some pages


### Jobs

- [X] A user can create a job
- [X] A user can view a job
- [X] A user can update a job
- [X] A user can delete a job

### Categories

- [X] The user can create a new Category by filling out a form. Each Category has a title (e.g. “Web Development”, “Education”, “Finance”).
- [X] When the user successfully creates a Category they are shown a page with the Category title.
- [X] When the user tries to create a Category that already exists, they are brought back to the page with the form to create a Category.
- [X] The user can view a list of all Categories on a single page, and each Category can be deleted from that page. There is also a link to “Edit” each Category, which takes the user to a form where they can update the Category.
- [X] When the user creates a new Job, they are required to select its Category from a drop down menu of existing categories. They also see a link to create a new Category.
- [X] When the user visits a page for a specific Category, they see a list of Jobs in that Category.

### Job Comments

- [X] When the user visits the page for a specific Job, in addition to information about the job there is a form that allows them to enter a Comment for that Job (e.g. “Spoke to hiring manager, Jacob. Plan to follow up Monday.”).
- [X] Each comment has content (also created_at and updated_at).
- [X] When the user submits a new comment, they are redirected back to the page for that specific job and the comment appears on the page.
- [X] The user can leave multiple comments on a job and the most recent comments are shown above older comments (in reverse of the order in which they were created).

### Company Contacts

- [X] When the user visits the page for a specific Company, in addition to information about the company there is a form that allows them to enter a Contact for that Company (e.g. “Penelope Santorini”, “Hiring Manager”, “penelope@wooo.com”).
- [X] Each Contact has a full name, position, email, and company (which relates to the company you’ve already created). It should be possible for a Company to have more than one Contact, but a Contact only works at one Company.
- [X] When the user submits a new contact, they are redirected back to the page for that specific company and the contact appears on the page.

### Analysis

- [ ] The user can visit `/jobs?sort=location` to view a list of the jobs sorted by `city`.
- [ ] The user can visit `/dashboard` to see
  - [ ] A count of jobs by `level_of_interest`
  - [ ] The top three companies ranked by average level of interest along with their respective average level of interest.
  - [ ] A count of jobs by `location` with a link to visit a page with jobs only in that location. The url should be `/jobs?location=Denver`.
- [ ] The user can visit `/jobs?sort=interest` to view a list of the jobs sorted by `level_of_interest`.

### Databases

- [X] The database has appropriate tables and columns to create relationships between tables
- [X] Table and column names follow convention

### Routes

- [X] Routes are defined for all functionality and not any additional functionality
- [X] All routes conform to RESTful conventions for resources
- [X] Routes to pages that are not specifically for resources stored in the database are not named in a way that an experienced developer would find surprising

### Controllers

- [ ] The developer has moved logic out of the controllers and into the models/POROs where appropriate.
- [X] The developer uses strong params in a private method
- [X] Instance variables being passed to views are appropriately named and limited in number

### ActiveRecord

- [X] ActiveRecord methods are used in models to supply all appropriate functionality
- [ ] Methods exist on the appropriate model
- [ ] Developers are not referencing other classes or `self` in models unnecessarily
- [ ] Ruby enumerables are not used where ActiveRecord methods could provide the necessary functionality
- [X] Developer can explain the ActiveRecord methods they used and the relationships between ActiveRecord models

### Views

- [X] Logic has been removed from views and controllers to the full degree possible
- [X] Developer ha minimized the number of variables passed to the view
- [X] Developer can articulately explain their strategies for extracting this logic
- [X] Developer uses partials to reduce duplication of code in the view layer

### User Experience/Usability

- [X] The application has been styled.
- [X] The application uses a balanced, considered color scheme.
- [X] The application implements a font (that is not the default font).
- [X] The application utilizes a nav bar.
- [X] The style shows evidence of intentional layout.
- [X] Space and text is balanced. White space is used to visually separate content.
- [ ] The application is easily usable. The user can intuitively navigate between different portions of the application without manually entering the URL into the nav-bar or using the back button on their browser.

### Testing

- [X] Project has a running test suite
- [X] Test suite includes robust feature tests
- [X] Test suite includes tests for validations
- [ ] Test suite includes tests for methods that they have created on the models

## Extensions:

### Tags

- [ ] The user is able to create new Tags from a form on the website.
- [ ] Each tag has a Title (e.g. “interview scheduled”, “waiting to hear back”, “email sent”, “research complete”, etc.).
- [ ] The user is able to view a list of Tags
- [ ] The user is able to delete Tags from the list of Tags.
- [ ] The list of tags also has a link to “Edit” each tag.
- [ ] When a user visits the site for a specific Tag they see a list of all jobs with that Tag.



### 1. Feature Completeness

* **Below Expectations: There are one or two features missing or incorrectly implemented**


### 2. Views

* Meets Expectations: Views make use of layout(s)


### 3. Controller

* Meets Expectations: Controller is generally well organized with three or fewer methods needing refactoring


### 4. Models

* **Below Expectations: Models are somewhat messy**
  * no model level methods at all!


### 5. ActiveRecord

* Meets Expectations: ActiveRecord is utilized wherever it can be. There is no Ruby where there should be ActiveRecord


### 6. Testing

* **Below Expectations: Project has sporadic use of tests**


### 7. Usability

* Meets Expectations: Project is usable, but needs more polish or navigation before it'd be customer-ready


### 8. Workflow

* Meets Expectations: Good use of branches, pull requests, and a project-management tool.
