<img src="./images/Soccer-logo.png">
##Application description

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

##Team members
+ Efosa Osamwonyi
+ Mike Stokes
+ Bobby Lopez  

##Technology used
+ Ruby on Rails
+ JQuery Ajax
+ Postgresql - database
+ HTML & CSS
+ Draw.io - ERD
+ Moqups.com - Wireframes


##Trello board
<a href="https://trello.com/b/tYYOSPAQ/project-3-bulbasaur">Bulbasaur Trello board</a>

##Artifacts
###Wireframes
<img src="./images/homepage.png">
<img src="./images/sign_up_page.png">
<img src="./images/itineraries.png">
<img src="./images/itinerariesid.png">
<img src="./images/matchesid-2.png">

###ERD
<img src="./images/ERDiagram.png">

###Tables

#### Users table
|id   |name| email  |password_digest   |
|---|---|---|---|
| 1  |efosa| efosa@gmail.com  |squirtle   |
| 2  |mike| mike@gmail.com  | charmander  |
| 3  |bobby| bobby@gmail.com  | mewtwo |
#### Itenaries table
|id   |name   |user_id   |
|---|---|---|---|
|1   |England Games  | 1  |
|2   |Barcelona-Camp Nou   |2   |
|3   |Germany games   |3   |
#### Matches table
|id|stadium_id|team1_name   | team2_name  | date  |itinerary_id|
|---|---|---|---|---|---|
|1|2 |Manchester United  | Chelsea  |05/01/2015   |1|
|2| 1 |Barcelona |Real Madrid   | 05/02/2015  |2|
|3| 3|Bayern Munich  | Manchester city  |05/04/2015   |3|

####Stadiums table
|id| name  |capacity   |city   | country  | home_team|
|---|---|---|---|---|---|
|1|Camp Nou   | 99,786  | Barcelona  | Spain  | FC Barcelona|
|2|Old Trafford   | 75,731  | Manchester  | England  |Manchester United FC|
|3|Allianz Arena   | 75,024  | Munich  | Germany  |Bayern Munich|
