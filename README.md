# <img src="https://skillicons.dev/icons?i=javascript" height="40" alt="javascript logo"  /> Random Card Generator

## Change your website styles during runtime using Javascript

## Instructions

Create an algorithm that randomly builds a card on every refresh:

1. Every time the website refreshes, a new random card needs to show.

2. The card must have one of the possible suits: Hearts, Spades, Clubs, or Diamonds.

3. The card value must be one of the following: 2 to 10, King, Queen, Jack or Ace (no joker).

In the end, the project needs to look similar to this demo:

<p align="center">
<img height="200px" src="https://github.com/breatheco-de/exercise-random-card/blob/master/preview.gif?raw=true" />
</p>

## Hints

- Remember that the first event of a website lifecycle is [onLoad (your code starts running there)](https://www.w3schools.com/jsref/event_onload.asp). You should generate a random number between 1 and 4 to pick a suit and another random number between 0 and 12 to pick a card number.

- Create a general `.card` class that applies the common styles to each card, and one additional CSS class for each suit: `.spade`, `.club`, `.heart` & `.diamond`.

- Apply the `.card` class to the entire div, but only apply one of the suit classes at a time, depending on what suit you want to apply. For example, a 3 of hearts will have this HTML declaration:

```html
<div class="card heart"></div>
```

- You can grab the icons from here (copy and paste into your code): ♦ ♥ ♠ ♣

## Extra difficulty

The following suggestions are not needed to successfully finish this project.

`+1` Add a button that generates a new card when clicked.

`+1` Add a timer that generates a new card every 10 seconds.

`+1` Allow the user to specify the card width and height using text inputs.

## Source

This exercise is part of the complete 4Geeks Academy Full Stack course:

[![4Geeks Academy](https://img.shields.io/badge/4Geeks%20Academy-blue.svg)](https://4geeks.com/interactive-coding-tutorial/todo-list)
