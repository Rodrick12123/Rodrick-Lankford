# Rodrick-Lankford
Website for obtaining data on World Cups
The github pages does not work with this app, because the postgress server need to be initialize first.

Future updates may include automatic initialization setup.

More instructions on running the app will be available here at a later date.

AUTHORS: Rodrick Lankford and Thea Traw

DATA: Our data is about all of the World Cups from 1930-2014, and it includes data about teams, players, matches, and the World Cups themselves. 

FEATURES CURRENTLY WORKING:
- Can choose All Cups checkbox on home page and it takes you to a page where all of the teams that have competed in a World Cup are loaded in a dropdown
- On that page, can choose a team, which takes you to the team's All Time page
- On team's All Time Page, World Cups that the team competed in load into dropdown
- Can choose a World Cup and that takes you to a page about the specific team in a specific World Cup (where the team's roster loads into a dropdown)
- Home button in nav bar takes you to home page
- Queries for "Teams that won gold medals" are working endpoints

FEATURES NOT YET WORKING:
- Cannot yet ask most queries specific to the page through the select box (you can ask about teams that won gold medals though!) - most api endpoints are written, but they don't display anything yet 
- Help button in navbar takes you to api/help right now, but will take you to better instructions/something more helpful later
- Queries to get the amount of medals a team has needs to be fixed
- titles for pages do not work right now (except for one)

Other notes:
- without page titles, the navigation is more difficult, so if this might be helpful, here's the flow:
[Homepage > World Cup Page (has a list of countries that have competed in any of the WCs selected on Homepage --> choose a country) > All time Team Page (has a list of WCs the team has competed in --> choose a WC) > One WC Team Page (has a list of the players on the roster at that World Cup)]
