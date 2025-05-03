# AnimeXWlist
An anime-themed wordlist for crossword constructor software.
Words are scored as 99. 
Because the set includes no non-letters, this could be changed to suit your needs in a text editor by find and replace.

## How to use
The Dictionary (.dict) data structure is preferred by Crossfire and Ingrid.
Crossword Compiler prefers a (.txt) text file.

There are multiple ways to download this dictionary.
 - Hit the Code button and clone a zip locally.
 - Click the file name and click "download raw file".
 - Check the Releases on the right side.

## Format
The dictionary is in the format below with no headers:

`word;score`

## Process
Data collection was done through a variety of means.
The included subset of anime series started by cleaning this data set: https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database?resource=download
I capitalized, eliminated numbers and special characters, removed whitespace and punctuation, and corrected errors to the best of my ability. Many series were excluded by an arbitrary personal popularity vibe check. Several were replaced with the more popular English or differently romanized name. At first, length was capped at 15 as per NYT daily puzzles, but a select few longer titles were slowly added back in.

For character names, I scraped an unoffical JSON API for MAL: https://api.jikan.moe.
A similar process of data cleaning took place, and additionally many name orders had to be reversed and many OU vowel clusters were simplified to more popular versions.

### Other Sources
https://en.wikipedia.org/wiki/List_of_Japanese_manga_magazines_by_circulation

https://en.wikipedia.org/wiki/List_of_manga_magazines 

https://en.wikipedia.org/wiki/List_of_anime_companies 

https://myanimelist.net/people.php

https://myanimelist.net/company
