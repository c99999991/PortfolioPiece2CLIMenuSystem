# PortfolioPiece2CLIMenuSystem

This repository contains a demonstration of the CLI Menu system that I created for the C1, C2, & C3 of COMP605 Data Structures
and Algorithms.

The purpose of this CLI menu system was to create a with tools to efficiently navigate the options and operation required 
of the given assignment.

The main function, takes an array of strings and two string and displays the options from the array, allowing the user to
navigate through the options, select or go back to the previous menu, as long as the user is within a sub menu and not the 
main menu, then they will be presented with an option to close the program.

![menu1](https://github.com/c99999991/PortfolioPiece2CLIMenuSystem/assets/142708292/66e8e531-b93d-40f7-9a27-0c2023e1da10)

This function return an integer, which is idealy used with a switch statement.

The following image displays how it was used in C3 to provide the user with access to the operations of an AVL tree.
The selected option is indicated by the "> [Selected Option] <" arrows around the selected option.

The string of text below the menu is the second string passed to the method, used to display any updates or information
to the user as they interact with the program to provide a better indication of the outcome of an operation, especially 
one with minimal or no visual indication of its sucess or failure.

![climenu2](https://github.com/c99999991/PortfolioPiece2CLIMenuSystem/assets/142708292/cefaf76b-a5f1-42b9-acb8-4d3386079a99)

The following function dynamicly generates an array from the files within the selected nested folder.
It uses the previously demonstrated menue function to allow the user so select the desired item.

![loadfile3](https://github.com/c99999991/PortfolioPiece2CLIMenuSystem/assets/142708292/bd3f40d9-05ab-471d-b9f2-e5df102b0fc1)

