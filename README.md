# HOUSE PARTY
[House Party Live Deployment](https://jhaarla.github.io/House-Party/)
![House Party screenshot](https://github.com/JHaarla/House-Party/blob/master/assets/images/HPthumb.png)

Welcome to House Party, the app that helps your party get off on the right track! From booze to tunes, we provide a user-friendly way to search for your favorite music and the perfect recipes to make your favorite drinks. Good drinks and good music, what else could you ask for?

### Instructions:

1. Click the logo on the landing page to be transported to the main site.

2. You will see an input box with the placeholder "Pick your poison!". In this input field, type in the beverage you'd like to look up. Hit "enter" or click the "search" button to find your beverage recipe. You can also try your luck with the "random" button. We'll serve up a recipe for a random beverage. You might just find your new favorite.

3. Your beverage along with all the ingredients and instructions will be displayed. Once you're done making your beverage, you can keep searching for other favorites. 

4. With a drink in hand, it's time to find some tunes for your House Party. Search for your favorite artist or genre of music in the "Music for your mood" input field. 

5. We'll bring up 5 playlists that'll keep the party going. Just select the one you want to listen to.

6. Of course we'll keep the music going while you search for another beverage or even a new playlist to keep the party going. 

7. Have fun & Enjoy!

### Under the Hood:

To make the magic happen, we're using AJAX calls to both YouTube and TheCocktailDB APIs. TheCocktailDB returns a JSON object for each search query that we pulled the relevant information from to display. The YouTube API also returns a JSON object that is used to display the relevant playlists. We also have several modals for communicating with the user. They are for error states - no search item entered or nothing returned. You can also show/hide the YouTube player - accomplished with some JavaScript toggle states. Our design began in Adobe XD and then implemented with Materialize CSS to create a dynamic and responsive UI. 

### House Party Coding Team:
* Jarkko Haarla
* Jeff Greco
* Bradley Cordle
[House Party Live Deployment](https://jhaarla.github.io/House-Party/)