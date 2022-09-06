# ACM Research coding challenge (Fall 2022)

## Summary of the Problem
I am relatively new to working with Kaggle Datasets in a Data Science setting, I previously had some experience in CS 4395 Human Language Technologies course. In there I learned about Natural Language Processing and used some of the libraries I used in this project. A for the Probelm I wanted to solve, I was going for an all around exploration of the data. The beginning was more basic commands and visualations of the data and I worked my way up to displaying it in a box plot and histogram.

##Process of Analyzing the Data
First I began with displaying the columns and number of rows followed by the head of the data. This was my way of "starting off small to make sure I could print basic data sections. Next I decided to make a function called return_counter that takes as input a data frame, column name, and limit. When called, it prints a dictionary of categorical values and how frequently they appear. I used it to print the 5 most common Makes from the data. Next I used it to get the 5 most common Years and lastly the 5 most common Exterior Colors. Next I defined a dictionary df_d1 and printed it to give me all the Years of all the Toyota cars in the dataset. Next I used the same dictionary to print the 5 most common years for Toyota vehicles. Lastly I used it to get the 5 most common Exteriro Colors of Toyota Vehicles. Next I defined a function return_statistics function that takes a data frame, a categorical column, and a numerical column. The mean and standard deviation of the numerical column for each category is stored in a data frame and the data frame is sorted in descending order according to the mean. I then used that function with the Categorical Column as 'Model' and the Numerical Column as 'Mileage'. It then outputs 15 Models and their mean Mileage and the standard deviation of the mileage as well respectively. Next I defined a function called get_boxplot_of_categories that function takes a data frame, categorical column, and numerical column and displays boxplots for the most common categories based on the limit. The input for the Categorical Column was 'Model' and the input Numerical Column 'Mileage'. Lastly I defined a function get_histogram that takes a data frame and a numerical column as input and displays a histogram. I called the function with the data frame and generated a histogram from ‘Price’. That completes all of my visualizations of the data. 
- Do different brands try to appeal to people looking for different thin
- Do different brands try to appeal to people looking for different things?
## How to submit your solution

1. [Create a **public** fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) of this repository and name it  `ACM-Research-coding-challenge-22F` (click the "Fork" button in the top right).

2. Replace this README file with a description ([written in Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github)) of your solution. Regardless of your success, describe the problem you set out to solve and how you did it. Split it up into sections with headers, and, if relevant, include figures.

3. Make sure to include all relevant files in your fork. If you made the project in a Kaggle notebook, click **File** → **Download Notebook** to download it as an `.ipynb` file.

4. You may have to "clone" the fork you made to edit files locally on your computer and "push" them to GitHub. Learn how to do that [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository).

4. Submit the link to your fork in this [form](http://apply.acmutd.co/research-coding-challenge).

## No collaboration policy

**You may not collaborate with anyone on this challenge.** You _are_ allowed (and encouraged) to use internet documentation. If you use existing code (either from Github, Stack Overflow, or other sources), **please cite your sources in the README**.

## Timing

Please don't spend too long on this project: **30 to 60 minutes** is reasonable. It's okay to put more time into your submission than that, but we don't expect you to get that much done; we really don't want this challenge to be a burden!

If you're *completely new* to this kind of project, however, it will likely take you more than an hour. This is a *densely useful* project to go through (you will learn a lot), so we believe this is justified.

## Assessment criteria

Submissions will be evaluated holistically, in combination with the rest of your application. We will consider your effort, use of external resources, how you approached the problem, and presentation, among other considerations.

## Support and questions

Feel free to ask for clarifications in the #research-qna channel in the [ACM UTD Discord server](https://discord.gg/nJxRdKdG4d)! You can also directly message Roman Hauksson on Discord: `RomanHauksson#3458`.
