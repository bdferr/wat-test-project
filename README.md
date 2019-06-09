# Namegame App

The original version of this app was provided by WillowTree, an app development company,
as a test project for potential employees. Much of this readme also consists
of the original instructions from WillowTree.

Learning your coworkers names while starting a new job can be very useful. Your test project is to make it happen! We have a simple version 
hosted at [https://wta-namegame.herokuapp.com/](https://wta-namegame.herokuapp.com/) which you can test. 
The API is located at [https://wta-namegame.herokuapp.com/api/game](https://wta-namegame.herokuapp.com/api/game).

We have provided you with a few files to get you started. Feel free to discard everything and start from scratch. You may use any framework or library you like.

If you need a simple http server, we recommend [http-server](https://www.npmjs.org/package/http-server).

## Option 1

Present the user with five faces and ask them to identify the listed name. This is essentially what is working already. To spruce things up, implement a few features of your choice.

1. Team mode. The API returns people who used to work here too. Current team members have titles and former team members don't. **Done!**
2. Stat tracking. How many correct / incorrect attempts did the user make? How long does it take on average for a person to identify the subject?
3. Reverse mode. Show five names with one picture.
4. Keyboard shortcuts. Power users love keyboard shortcuts; maybe add numbers for faces for mouse free fun.
5. Local scoring. The server might not accept scores, but you can always track it locally. Make metrics of your own and have a leader board!
6. Matt Mode. Roughly 90% of our co-workers are named Matt, so add a challenge mode where you only present the users with a Matt. **This was already done.**
7. Hint mode. As people wait, faces disappear until only the correct one is left.

My own ideas, already implemented in wta-app1.html, are here:

8. Sort people by the last letter of their last names.

9. Exclude the people who either have no profile pictures or have only a generic WillowTree logo as a picture.

10. Exclude duplicates. 

11. Implement a button to select only women and another to select only men.

12. Choose a set of either all women or all men; a coin toss will make both equally likely.


13. Create German and Italian versions and let the user switch back and forth between them.

## Option 2

Feel like taking the path less trodden? Do you know a better way to learn faces than to present five options and a name? Come up with your own memory game!

## German Vocab App

My efforts to create a new app from scratch are still in progress, but the intention
is to help the user practice German vocabulary. A script will make an AJAX call to a JSON file 
and make random selections, displaying an English term, a corresponding image,
and five German terms for the user to select from, one of which corresponds to the English word. 
Clicking an option will yield a message indicating whether the user has selected the correct term.

The app already features buttons to provide terms with only a particular gender --
German nouns are either masculine, feminine, or neuter. The user can also click a button
to toggle the user interface between German and English.

I hope to implement a scoring system in line with item 2 under option 1 above.
At a minimum this would keep track of the number of correct and incorrect guesses
and calculate the percentages of the total which each represents.

The relevant HTML file is german-vocab-game.html. 
Currently this project employs the Javascript library jQuery and I hope to also implement React and Lodash.