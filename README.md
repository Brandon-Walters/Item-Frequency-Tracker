# Item Frequency Tracker

## Table of Contents
- [Introduction](#introduction)
- [Class Definition](#class-definition)
- [Main Function](#main-function)
- [Menu Options](#menu-options)
- [Input/Output Operations](#inputoutput-operations)
- [Error Handling](#error-handling)

## Introduction
The Item Frequency Tracker is a C++ program that tracks the frequency of items read from an input file. It provides functionality to check the frequency of a specific item, print the frequency of all items, and display a histogram of item frequencies.

## Class Definition
The `tracker` class is responsible for tracking item frequencies. It uses a map to store items and their corresponding frequencies. The class provides methods to add items, get the frequency of a specific item, get the frequency of all items, load data from a file, and save data to a file.

## Main Function
The `main` function is the entry point of the program. It creates a `tracker` object, loads data from an input file, and saves it to a backup file. It then enters a loop to handle user input and execute menu options until the user chooses to exit the program.

## Menu Options
The program provides the following menu options:
1. Check item frequency: Allows the user to check the frequency of a specified item.
2. Print frequency of all items: Prints the frequency of all items tracked by the program.
3. Print histogram of all items: Displays a histogram of the frequency of all items.
4. Exit: Exits the program.

## Input/Output Operations
The program reads input data from a file specified by the user and saves the tracking data to a file named "frequency.dat". It interacts with the user through the command line interface, displaying menu options and prompting for user input.

## Error Handling
The program handles errors related to file input/output operations using exception handling. If an error occurs while opening or reading the input file, an error message is displayed, and the program terminates with a non-zero exit status.