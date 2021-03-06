---
layout: post
title: Project Showcase common-actors
---

[common-actors](https://github.com/HarryHawkins/common-actors) is a simple Python script that returns common actors (and actresses) from movies specified by the user.

It uses the [IMDbPY](https://imdbpy.github.io/) python package. 
I created this script because I couldn't remember the name of an actor, but I could think of some movies that he was in. This script found the Actor for me. 

It is very simple to use...

Simply:
- Install Python 3
- Install IMDbPY
 `pip3 install imdbpy`
- Run the script
    `python3 common-actors.py`

Extra features:
- Run with `-wiki` flag to automatically open the common actors in wikipedia 
    `python3 common-actors.py -wiki`

Examples:

    user@pc:~/projects/python$ python3 common-actors.py 
    Welcome to common-actors! 
    This tool will give you the common actors from a selection of given movies

    How many movies would you like to enter? 3
    Enter movie number 1: The Matrix
    Enter movie number 2: The Matrix 2
    Enter movie number 3: John Wick
    Movie 1 found: The Matrix
    Movie 2 found: The Matrix Reloaded
    Movie 3 found: John Wick
    Common actors found 1: 
    Keanu Reeves

    user@pc:~/projects/python$ python3 common-actors.py 
    Welcome to common-actors! 
    This tool will give you the common actors from a selection of given movies

    How many movies would you like to enter? 2
    Enter movie number 1: Pulp Fiction
    Enter movie number 2: Kill Bill 
    Movie 1 found: Pulp Fiction
    Movie 2 found: Kill Bill: Vol. 1
    Common actors found 1: 
    Uma Thurman
    
    user@pc:~/projects/common-actors$ python3 common-actors.py 
    Enter your first movie: The matrix
    Enter your second movie: The matrix 2
    First movie found:  The Matrix
    Second movie found:  The Matrix Reloaded
    Common actors found  6 : 
    Keanu Reeves
    Carrie-Anne Moss
    Nash Edgerton
    Gloria Foster
    Laurence Fishburne
    Hugo Weaving

    user@pc:~/projects/python$ python3 common-actors.py 
    Welcome to common-actors! 
    This tool will give you the common actors from a selection of given movies

    How many movies would you like to enter? 3    
    Enter movie number 1: inception 
    Enter movie number 2: interstellar
    Enter movie number 3: dunkirk
    Movie 1 found: Inception
    Movie 2 found: Interstellar
    Movie 3 found: Dunkirk
    Common actors found 1: 
    Michael Caine



