# unbeatable-chess.AI

Play it live here! 

## Project Overview
A chess game built with Minimax algorithm and Alpha Beta Pruning optimization
 
## Screenshots
Include logo/demo screenshot etc.

## Tech/framework used

- JavaScript
- Node.js
- JQuery
- HTML/CSS

## Features

- Basic logic is to direct the computer player to achieve maximum weights for itself and minimizes the total weights of the opponent by using Minimax algorithm. For every move the computer is going to loop through the entire board, calculate the weights for every potential move every piece can achieve to pick the move that maximizes it's total weights(ex. get a piece into a position that threatens an opponent's piece without endangering itself); in the mean time, do the same calculation for the opponent but pick the move that's going to have the maximum negative impact for him(ex. capture an opponent's piece).

![chess1](https://user-images.githubusercontent.com/38970716/50548479-36875580-0c1b-11e9-8f2b-5dbe6fbd4ba5.gif)

- The search depth is default to 3, that means for every move the computer is going to loop through the board three times in a recursive fashion to foresee three steps ahead and make the best move. Testing has shown that depth beyond 3 will make the calculation extremely slow due to the process is exponential in nature

![peek 2018-12-30 09-25](https://user-images.githubusercontent.com/38970716/50548637-13aa7080-0c1e-11e9-86b7-5a06ee8b78cd.gif)

- other features including applying Alpha Beta Pruning technique to optimize the runtime of the algorithm. As well as using JQuery and Css to style the potential moves of a piece when the cursor hover over it. 

## Code Example
Show what the library does as concisely as possible, developers should be able to figure out **how** your project solves their problem by looking at the code example. Make sure the API you are showing off is obvious, and that your code is short and concise.

## Installation
Provide step by step series of examples and explanations about how to get a development env running.

## API Reference

Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Tests
Describe and show how to run the tests with code examples.

## How to use?
If people like your project they’ll want to learn how they can use it. To do so include step by step guide to use your project.
