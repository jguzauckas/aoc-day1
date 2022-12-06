# National Computer Science Education Week - Advent of Code

This week is National Computer Science Education Week! To celebrate, I wanted to try a fun coding challenge that is presented every year: Advent of Code.

This is a project someone has made that provides up to 25 days of coding challenges throughout December, while gamifying the process. Each day presents an initial puzzle to solve with programming, and when completed offers a follow-up puzzle, offering a total of 50 puzzles over the course of the month. Many of these can get very complex very quickly, but the initial days of puzzles are approachable and I think would make a good challenge for our class.

## Instructions

The first step is to go to [Advent of Code](https://adventofcode.com/) and click "Log In" at the top, and log in using your GitHub account. Once you've logged in, you'll be able to access your inputs for the puzzles and try them yourselves!

At the bottom of the page click on Day 1 and read about the puzzle! You can click a link to access your "puzzle input", which has the information you have to use to solve. Copy all of that text and paste it into the `input.txt` file and save it. Then open the `input-transform.py` file and run the code. You should now see all of your numbers in the `input.json` file for your use in your program!

One modification I made is that instead of there being blank spaces in your list, the number `-1` has been placed there. Use that to help you determine when you are changing sections!

Your goal is to solve parts 1 and 2 of the day 1 puzzle! This is going to be challenging and might require trying some different things.

For your reference, I have provided by puzzle input in the `mrg-input.json` file, formatted just like yours, so you can run your code on my input to see if you get the right answers. The correct answers for my input are:

- Part 1 -> `69626`
- Part 2 -> `206780`

If your code can get the right answer with my input, chances are it can get the right answer with yours!

**Warning:** Be careful entering answers many times to the Advent of Code website, it will slowly make you wait longer before each submission!

To begin coding, create a Python file (ends in `.py`) and use `json` to read your input list into your program to use!
