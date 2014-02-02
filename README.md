Link to the deployed app
------------------------
http://morning-coast-8317.herokuapp.com/

Goal of the homework
--------------------
Create a static copy of the Google homepage using html and css by creating a new view/controller in a Rails app. Also to start to learn how to deal with the Rails asset pipeline and use DRY techniques to separate navbars/footers from specific content of every page.

Issues I ran in to
------------------

When first deploying to Heroku I received the following error:
"Precompiling assets failed"
So I followed the solution on Heroku's docs to precompile assets locally:
https://devcenter.heroku.com/articles/rails-asset-pipeline

Also, in general it just a LOT of trial and error to get all the css/html right. I spent the most amount of time on the following elements:

1) Getting the nav bar aligned and not overlapping with the center'd Google image

2) Styling the Search input so that it was the right size, the right border colors (inactive and active states), and the right alignment of the voice search icon.

3) Getting the footer aligned to the bottom of the page and having it stay there.

There were no specific solutions to these problems, just a lot of trial and error.

Project ideas
-------------

1) A meal plan suggester. The user will enter their current weight, height, activity level, and desire to to gain, lose, or maintain weight, and the app will suggest three meals based off pre-loaded menu items from select restaurants around campus. The user will also have the option to add additional menu items and corresponding nutritional information.

2) Facebook friendship slideshow generator. A user will choose one or more friends from Facebook, then a slideshow will be generated with appropriately cheesy and emotional music to be played alongside it. The user will have the option to share the slideshow.

3) A travel suggester on a budget. A user will enter approximate desired travel destination (anywhere from dates to length to continent) and a budget, and then we will give you choices of full itineraries. You can adjust your estimated spending on food, etc to make it more accurate.




