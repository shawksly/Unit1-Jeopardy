# Upright Unit 1 - Jeopardy Project

#### URL: [https://github.com/shawksly/Unit1-Jeopardy](https://github.com/shawksly/Unit1-Jeopardy)

## Status === Complete

## Languages

HTML, CSS

## Pseudocode
The website is for a game of Jeopardy. It is not meant to be functional in this state.

#### Flow / Page Description
1. The user arrives at a page with a play button
2. Upon clicking play, they are taken to the first round page, which shows:
    1. The title
    2. Who's turn it is
    3. A 6x6 grid with categories along the to row, and increasing clue prices going down ($200-1000)
        1. Each of these clue screens are responsive to pointer movement with a change of size and slight change of text color
    4. A text box for inputting a guess
    5. A guess button and a pass button next to each other, both non-functional
    6. Player scores on either side of the screen
    7. A next round button and empty space for a previous round button
    8. And a footer that links back to the home page
3. Upon clicking next round, they are taken to the second round, which is identical to the second page except:
    1. The player has changed
    2. The clue screens have their prices increased, but still increase going down ($400-$2000)
    3. There is a previous round button that links to the previous page
4. Upon clicking the next round button, they are taken to the final round page, which is identical except for:
    1. Instead of a large grid:
        1. Only one larger category screen is shown
        2. And one larger screen with the final question.
    2. Instead of a guess text box:
        1. There is a box for amount of points bet
        2. And a box for a final answer.
    3. Instead of guess and pass buttons:
        1. There is a disabled bet button.