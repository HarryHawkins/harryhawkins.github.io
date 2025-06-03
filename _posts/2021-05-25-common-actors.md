---
layout: post
title: Project Showcase common-actors
---

## Find Common Actors Across Movies with a Simple Python Script

Have you ever struggled to remember an actor's name, even though you can recall a few movies they were in? That’s exactly why I built **[common-actors](https://github.com/HarryHawkins/common-actors)** - a simple Python script that helps you find common actors (and actresses) from a list of movies.

## How It Works

The script uses the **[IMDbPY](https://imdbpy.github.io/)** Python package to fetch cast lists for each movie you enter. It then returns the actors and actresses who appear in *all* of the movies you specified.

## Why I Built It

I found myself trying to remember the name of an actor, but the only thing I could recall was several movies he had been in. I couldn’t find him through regular google searches, so I created this tool to help me - and now it can help you too.

## How to Use It

1. **Install Python 3**  
   Make sure Python 3 is installed on your system.

2. **Install IMDbPY**  
   Open a terminal and run:  
   ```bash
   pip3 install imdbpy
   ````

3. **Run the Script**
   In the terminal, navigate to the folder with the script and run:

   ```bash
   python3 common-actors.py
   ```

   You’ll be prompted to enter movie titles. The script will then display any actors who appear in all the specified films.

## Extra Feature: Wikipedia Lookup

You can also use the `-wiki` flag to automatically open each common actor's Wikipedia page in your browser. This is useful for quickly checking their bios or confirming who you were thinking of.

Example:

```bash
python3 common-actors.py -wiki
```

## Examples

```bash
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
```

```bash
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
```

```bash
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
```

```bash
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
```
