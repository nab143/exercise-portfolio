# Portfolio

## Bar Chart & Scatterplot

**DUE:** March 4, 2019, Noon.

## Before You Begin

Set up a repository for your portfolio in your own GitHub account. Follow the instructions provided in the [`exercise-portfolio`](https://github.com/umiami-data-viz/exercise-portfolio) repo of the course GitHub.


## Instructions

You have been provided three data sets in the `data` directory:

- mlb-standings.csv
- nfl-rushing.csv
- nhl-special-teams.json

Using these, you will create one **bar chart** and one **scatterplot** using [d3](https://d3js.org/).

Each visualization should be in a separate file (i.e. `bar-chart.html`, `scatterplot.html`) in your exercise portfolio.

You may mix-and-match which data set you want to use a visualization, but you *must* use different data sets. (For instance, if you choose to create a bar chart using `mlb-standings.csv`, you must use one of the other two data sets for the scatterplot.)

Make sure each visualization has all required details (i.e. a title, text description, labels, axes, etc.) — not just the data!


### Data Sets

Each data set presents unique information. Below is a breakdown of suggestions for what statistics you may want to visualize.

#### `mlb-standings.csv`

This data set represents the 2018 league-wide standings in Major League Baseball. This includes additional data related to scoring and record splits. It is presented using comma-separated values (csv).

**Bar Chart:** You have three options: Wins (`w`), Losses (`l`) or Win Percentage (`pct`).

**Scatterplot:** Show the relationship between `runs` and `runs_against`. Use `wins` to represent the size of each point.


#### `nfl-rushing.csv`

This data set represents 2018 National Football League rushing statistics as it relates to players who are either running backs (RB) or fullbacks (FB). It is presented using comma-separated values (csv).

**Bar Chart:** You have two options: the number of fumbles (`fum`) or touchdowns (`TD`). *Only include players who had 150 or more attempts (`att`). (You should end up with 28 players.)*

**Scatterplot:** Show the relationship between yards (`Yds`) and touchdowns (`TD`). Use fumbles (`fum`) to represent the size of each point.


#### `nhl-special-teams.json`

This data set represents the 2017-18 league-wide standings in the National Hockey League. This includes additional data related to scoring, special teams, shots and faceoffs. It is presented using JavaScript Object Notation (json).

**Bar Chart:** You have multiple options: Wins (`wins`), Points (`points`), Points Percentage (`pointPctg`) or Goals For (`goalsFor`).

**Scatterplot:** Show the relationship between power play percentage (`ppPctg`) and penalty kill percentage (`pkPctg`). Use `pointPctg` to represent the size of each point.


## Submitting Your Work

**Email Prof. Brown with a link to your exercise portfolio no later than March 4, 2019, Noon.**


## Review

Profs. Brown and Figueroa will randomly select students on March 4 to go over your visualizations in class.

Students are expected to make notes of improvements to be completed before the final submission of the portfolio is due at the end of the semester. Exercises which remain unchanged will receive deductions.

Even if you are not selected, it is recommended you take notes on what can be improved in the visualizations presented as it may relate to your own work.


## Reminder

Students are expected to complete these visualizations individually. **Your code is expected to be unique.** There are at least six combinations of possible visualizations on the data sets alone.

Students who have identical (or near-identical) code will earn a zero on the assignment when portfolios are graded.

**Good luck!**
