---
layout: post
title: Every Opening
---

## Every Opening

Every Opening is a project I made as a final exam for my Artv 10300 class in Spring Quarter 2026 with Professor Jason Salavon. The project features a live rendering of the top 500 most frequent chess openings played by real humans. 

Data was obtained from [Lichess](https://database.lichess.org/) and used the April 2026 dataset of 90,000,000 games. I built a program to analyze these games into a json file that could then be read by the output file to generate the live graphics of all 500 games.

During this project, I noticed interesting things about the dataset, such as there were at least three one move games. They were 1. e4, 1. d4, and 1. Nf3. At first, I thought something had gone wrong, as in the output file, those games showed a 99%+ win rate for white, wheras all other openings had a roughly 50/50 split. However, I realized those were games that had been started, and then immediately quit by one of the players (99% of the time being the black player).

You can view the innerworkings of the project on my [GitHub](https://github.com/dmarchese155/projects) in the chessdata folder. The project could be remade with a larger dataset if you have the computing power or with a more updated dataset if you like using the parse_lichess_openings.py file. You can see the final product yourself by downloading and running the chess-openings500.html file.
