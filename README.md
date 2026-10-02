# Skyscrapers
This repository is a passion project of mine, making a puzzle game from scratch. At university, I was part of a committee responsible for organising a puzzle road trip to Belgium, and I used this project to create interest in the puzzle race.

## Technologies
The project uses plain JavaScript with HTML and CSS to construct the levels. It makes use of cookies to store which level you have completed.

## The Puzzle
The goal in Skyscrapers is to place all towers in a square grid. Certain constraints hold:
- In every row and column, a skyscraper 'height' (number) can only appear once
- Every number at the edge of the squares represents how many towers are visible from that direction. This means that a tower of height 1 is not visible from a certain direction if a tower of heigt 2 or 3 stands in front of it.
- You can click on the numbers at the side to see in what way the constraints are already met. There is also a hint system that can guide you towards understanding the rules better.
- The puzzles get bigger and more complicated as you progress. Have fun!