Battle Challenge
==================

This is a solution to the Makers Academy's [Battle Challenge](https://github.com/makersacademy/course/blob/master/intro_to_the_web/00_challenge_map.md).

This uses a test-driven approach with both unit tests using [RSpec](http://rspec.info) and
feature tests using [Capybara](https://github.com/jnicklas/capybara). The aim is to create a
[Sinatra](http://www.sinatrarb.com) web application.

##Installation
Clone the repository and change into the directory:

```
$ git clone git@github.com:Andrew47/battle-challenge.git
$ cd battle-challenge
```

##Using the program
Run `ruby app.rb` and click the following link: [http://localhost:4567](http://localhost:4567).
The home page is as follows:
![alt "home page"](/public/images/home_page.png)

Type the name of player 1 and 2. Choose whether Player 2 is a computer. Then click 'Submit'.

Then you can choose to attack (which is more likely to deal a higher damage), paralyse (which could lead the opponent to miss a turn), or poision (which leads the opponent to lose damage over time).

## User Stories
```
As two Players,
So we can play a personalised game of Battle,
We want to Start a fight by entering our Names and seeing them

As Player 1,
So I can see how close I am to winning
I want to see Player 2's Hit Points

As Player 1,
So I can win a game of Battle,
I want to attack Player 2, and I want to get a confirmation

As Player 1,
So I can start to win a game of Battle,
I want my attack to reduce Player 2's HP by 10

As two Players,
So we can continue our game of Battle,
We want to switch turns

As Player 1,
So I can see how close I am to losing,
I want to see my own hit points

As Player 1,
So I can lose a game of Battle,
I want Player 2 to attack me, and I want to get a confirmation

As Player 1,
So I can start to lose a game of Battle,
I want Player 2's attack to reduce my HP by 10

As a Player,
So I can Lose a game of Battle,
I want to see a 'Lose' message if I reach 0HP first
```

##Contributors
* [Andrew Burnie](https://github.com/Andrew47)
* [Emma Beynon](https://github.com/emmabeynon)
* [Kirk Smith](https://github.com/SmithKirk)
