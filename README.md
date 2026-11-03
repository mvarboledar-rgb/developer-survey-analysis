# Developer Survey 2024: work models, pay and tech trends

Analysis of the Stack Overflow Developer Survey 2024 (65,437 people, 185 countries).
This was my capstone project for the IBM Data Analyst Professional Certificate.

The question I wanted to answer: if a company is hiring, training or marketing to
developers, what should it know about how they work, how much they earn and what
they want to learn next?

## Why I did this project

I come from marketing and market research. For almost three years I coordinated
polls and surveys in Medellín, Colombia. I took the IBM Data Analyst certificate
to learn more technical tools and move into more specialized data analysis.

What caught my attention was how different this survey is from the polls I used
to run. Ours were face-to-face: if someone didn't want to take part, we skipped
them, and everyone who agreed answered every question. This survey is online and
every question is optional, so 64% of people chose not to share their salary.
That changed how I cleaned the data: instead of filling the gaps with a typical
value, I only used the people who actually answered each question.

I was also curious about why remote developers report higher pay. Since this is
a correlation, I wanted to rule out the most obvious explanation: remote work is
more common in higher-paying countries like the US. So I repeated the same
comparison inside a single country to see if the gap still holds.

## What I found

- 80% of developers work remotely or hybrid. Only 20% go to the office every day.
- The median yearly salary is $65,000, but it varies a lot: the middle half
  earns between $33k and $108k.
- Remote developers report higher pay than in-person developers in every age
  group from 25 to 64 (around $112k vs. $76k at ages 45-54).
- Python, JavaScript and SQL are the languages people most want to work with.
- PostgreSQL is the most used database and ChatGPT the most used AI tool.
- 64% skipped the salary question and 55% skipped job satisfaction, so every
  result shows how many people it is based on.

## What I did

1. Collected data from an API, web pages and the survey file (CSV and SQLite).
2. Cleaned it: duplicates, missing values, and turning text answers like age
   ranges into numbers.
3. Explored distributions, outliers and correlations.
4. Built charts to present the results.

## Tools

Python (pandas, Matplotlib, Seaborn), SQL, Jupyter

## Files

- `analysis/` - the main notebook with the full analysis (start here)
- `dashboard/` - data preparation I did for the course dashboard
- `labs/` - the step-by-step course labs
- `images/` - charts

You can open the notebook directly in Google Colab. It downloads the data on its own.

---

Manuela V. Arboleda Restrepo · [LinkedIn](https://linkedin.com/in/manuela-arboleda)
