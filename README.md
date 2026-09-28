# Emoji Faces 😊

A simple Python program that converts text-based emoticons into their corresponding emojis.

## About the Project

I built this project as part of **CS50's Introduction to Programming with Python** by Harvard University.

The program takes a string from the user and converts `:)` into a smiling face emoji and `:(` into a sad face emoji.

All other text remains unchanged.

## How It Works

The program uses a `convert` function to process the input string and replace the supported emoticons with emojis.

For example:

```text
Input:
Hello :)

Output:
Hello 🙂
```

It can also handle multiple emoticons in the same sentence:

```text
Input:
Hello :) Goodbye :(

Output:
Hello 🙂 Goodbye 🙁
```

## What I Practiced

While working on this project, I practiced:

* Defining and using functions
* Working with strings
* Replacing parts of a string
* Taking input from the user
* Returning values from functions
* Keeping the rest of the input unchanged

## Technologies

* Python

## What I Learned

This project helped me practice creating functions and working with strings in Python.

I also learned how a simple string-processing function can be used to modify specific parts of user input while leaving the rest of the text unchanged.

## Course

This project was completed as part of **CS50's Introduction to Programming with Python** by Harvard University.
