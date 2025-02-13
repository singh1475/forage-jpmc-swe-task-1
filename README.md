# JPMC Task 1
Starter repo for task 1 of the JPMC software engineering program


You’ve been asked to assist with some development to add a chart to a trader’s dashboard allowing them to better identify under/over-valued stocks.

The trader would like to be able to monitor two historically correlated stocks and be able to visualise when the correlation between the two weakens (i.e. one stock moves proportionally more than the historical correlation would imply). This could indicate a potential trade strategy to simultaneously buy the relatively underperforming stock and sell the relatively outperforming stock. Assuming the two prices subsequently converge, the trade should be profitable.

Most data visualisation for our traders is built on JPMorgan Chase's Perspective data visualisation software, which is now open source. If you want to explore that, a link is provided in the resources section.

Before implementing this request using perspective, first, you’ll need to interface with the relevant financial data feed and make the necessary adjustments to facilitate the monitoring of potential trade opportunities.


Task 1: Interface with a stock price data feed

<h1>
Here's what you need to do</h1>
For the first task of this project you will need to accomplish the following:

Set up your local dev environment by downloading the necessary files, tools and dependencies.
Fix the broken client datafeed script in the repository by making the required adjustments to it.
Generate a patch file of the changes you made
(optional): Add unit tests in the test script in the repository.

<h1>Set up your dev environment</h1>
Set-Up

Before you can tackle any software development task, you need to set up your development environment. You can think of your local development environment as a virtual workbench with all the tools necessary to work on your project. To set up your dev environment, follow these instructions:

Install python 3 to your system - any recent version of python 3 will work fine, though the most up-to-date version is advisable. If you need help with this step, check out this excellent guide from real python: https://realpython.com/installing-python/
 
Fork and clone the starter repo here: https://github.com/theforage/forage-jpmc-swe-task-1
IMPORTANT! Uncheck the “Copy the main branch only” box in the fork dialog on GitHub. A model answer has been provided in a separate branch from main.
if you are unfamiliar with forking, cloning, or git in general, take a look at the first two chapters of the git book here: https://git-scm.com/book/en/v2
 
Open the project in your IDE of choice - if you don’t have a favourite python IDE yet, take a look at Pycharm Community Edition. It’s a well-designed IDE by Jetbrains packed with features and plugins, powerful enough to work on the most complex projects, and entirely free.
 
Create a new virtual environment in the project root. Pycharm can do this automatically for you using the “configure python interpreter” option in settings.
 
Install all project dependencies. These are listed in the requirements.txt file.
 
Congrats, you’ve got your local development environment up and running! Now it’s time to make changes to the codebase…


