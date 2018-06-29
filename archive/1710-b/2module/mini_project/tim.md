### Project Option 1: IdeaBox

Let's create an app to record your ideas. Host your app live on Heroku.

#### Ideas

* [ ] An idea can be created by a user.
* [ ] An idea can be edited/updated only by the user that created it.
* [ ] An idea can be destroyed only by the user that created it.
* [ ] When a user types a new idea into the form, there is a [selection dropdown](http://guides.rubyonrails.org/form_helpers.html#option-tags-from-a-collection-of-arbitrary-objects) for choosing the correct category. See Categories below for more information.

#### Categories

* [ ] Ideas belong to a category.
* [ ] Categories can be created and destroyed by a logged-in admin user (regular logged in users cannot create categories).
* [ ] Categories can be destroyed by a logged-in admin user (regular logged in users cannot destroy categories).

#### Images

* [ ] Users can add an image to their own idea.
* [ ] An image can have many ideas and an idea can have many images.
* [ ] Images can only be created by an admin user.
  * The most simplistic way to implement images is to store a url to an online image. If you're feeling fancy and want to upload your own images, check out [Carrierwave](https://github.com/carrierwaveuploader/carrierwave) or [Paperclip](https://github.com/thoughtbot/paperclip).

#### Authentication and Authorization

* [ ] Users need to log in to see their ideas.
* [ ] Users can only see their own ideas -- they should not be able to visit another user's page.
* [ ] Users cannot create ideas for other users.
* [ ] Users cannot create new categories -- only the admin can do that.
* [ ] Users cannot create images -- only the admin can do that; however, a user can assign an image to their idea.
* [ ] Visitors can create user accounts.

#### Optional Extensions

* Implement Twitter, Github, or Facebook OAuth login
* Use HAML for your views
* TDD using RSpec instead of Test::Unit
