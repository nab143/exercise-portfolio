# Portfolio

## Filtering, Updates and Interactivity

**DUE:** April 8, 2019, Noon.


## Before You Begin

This visualizations should be built utilize `template.html` from your [`exercise-portfolio`](https://github.com/umiami-data-viz/exercise-portfolio).


## Instructions

Create one **interactive bar chart** and one **interactive line chart** using *only* [d3](https://d3js.org/) and [lodash](https://lodash.com/).

Each visualization should be in a separate file (i.e. `interactive-bar.html`, `interactive-line.html`) in your exercise portfolio.

Make sure each visualization has all required details (i.e. a title, text description, labels, axes, etc.) — not just the data!

### Interactive Bar Chart

Included in `data` are standings for MLB Spring Training (`spring-training.csv`). During spring, teams are divided into two leagues: Grapefruit and Cactus.

Create a bar chart which displays one league at a time, sorted by win percentage (`pct`). Teams which share the same win percentage should be sorted alphabetically.

Add buttons which allow a person to toggle between the Grapefruit League and Cactus League.


### Interactive Line Chart

Included in `data` is the all-time monthly stock data for the Walt Disney Company (`DIS.csv`).

Create a line chart, using the **Close** price as the data. Include a line which intersects with the highest closing price. Identify the purpose of this line with a label.

Add a tooltip which appears on hover and displays the:
- Month and Year (i.e. Jan 2019)
- High ($96.43)
- Low ($90.83)

*TIP:* To make the hover effect work well, make your stroke-width for the line big (though don't make it so big the design is bad). You need to give users enough to hover over to make the tooltip effective.


## Submitting Your Work

**Email Prof. Brown with a link to your exercise portfolio no later than April 8, 2019, Noon.**

Late submissions or incomplete exercises will receive a zero (0).


## Review

Profs. Brown and Figueroa will randomly select students on April 8 to go over your visualizations in class.

Students are expected to make notes of improvements to be completed before the final submission of the portfolio is due at the end of the semester. Exercises which remain unchanged will receive deductions.

Even if you are not selected, it is recommended you take notes on what can be improved in the visualizations presented as it may relate to your own work.


## Reminder

Students are expected to complete these visualizations individually. Do not copy/paste code from notes, exercises or the book. **Your code is expected to be unique.**

Students who have identical (or near-identical) code will earn a zero on the assignment when portfolios are graded.

**Good luck!**
