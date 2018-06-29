### Project Option 2: GifGenerator

**MEETS EXPECTATIONS**

Create an app where users can "favorite" gifs.

#### Gifs

* [X] Admins can generate gifs by entering a one-word search term in field and then clicking "generate gif". This should create a new gif in the database. This feature is not available to regular users.
  * Gifs should have an image_path. See above "Images" in project #1 for more info on implementing images.
  * Use the [GiphyApi](https://github.com/giphy/GiphyAPI) to generate gifs.

#### Favoriting

* [X] Regular users can mark a gif as "favorite".
* [X] Regular users can see a list of all of the gifs they've marked as favorites.
* [X] Regular users cannot delete a gif; they can only "unfavorite" it for themselves.
* [X] Regular users should be able to see all gifs sorted by category.
* [X] Regular users should be able to see favorited gifs sorted by category.

#### Categories

* [X] Gifs belong to a category (category is the original word that was searched for by the admin).
* [X] Categories can be created by a logged-in admin user (regular logged in users cannot create Categories).
* [X] Categories can be destroyed by a logged-in admin user (regular logged in users cannot destrCy categories).

#### Authentication and Authorization

* [X] Users need to log in to see their favorited gifs.
* [X] Users can only see their own favorited gifs -- they should not be able to visit another user's page.
* [X] Users cannot create favorites for other users.
* [X] Users cannot create new categories -- only the admin can do that.
* [X] Users cannot create gifs -- only the admin can do that.
* [X] Visitors (non-registered users) can create user accounts.

#### Optional Extensions

* Implement Twitter, Github, or Facebook OAuth login
* Use HAML for your views
* TDD using RSpec instead of Test::Unit
