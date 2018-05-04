# Basic Data Visualization

## Objective

Students will learn how to create basic data visualization with Python and Pygal. They will learn the importance of visualizing data to better understand patterns, trends, and correlations.

## What is Data Visualization?

Data visualization helps people understand the significance of data by placing it in a visual context. Patterns, trends, and correlations that might go undetected in text-based data can be exposed and recognized easier with visualizations.

## Prerequisites

None. Students do not need prior knowledge of Python as this lesson is a designed for beginners.

## Concepts

| Python    | Description                                                                                                      | Example                    |
| --------- | ---------------------------------------------------------------------------------------------------------------- | -------------------------- |
| Python    | Python is an interpreted, object-oriented, and user-friendly programming language                                | n/a                        |
| Variables | Variables are used to store data types like text or integers                                                     | my_name = 'ada'            |
| Text      | Any piece of data wrapped in single `'...'` or double `"..."` quotes                                             | 'some text' or "more text" |
| Integer   | A plain, whole number                                                                                            | 1, 50, or 300              |
| Function  | Blocks of code that we can build to do a specific task and call on at a different time                           | def my_function()          |
| Libraries | Also known as packages, help programmers develop applications faster because they come with useful built-in code | Pygal, lxml                |

## Resources

Pygal - http://pygal.org/en/stable/
To find how to use the different charts available, please look into the documentation section of the website.

## Assignment

#### Getting Started

You will need the following library/packages for this project. Please install the following if you haven't already:

* Pygal - `pip3 install pygal`
* lxml - `pip3 install lxml`

#### Challenge

Students will need to research what data set they want to use to create their visualizations. Here are a few topics that can easily be found online:

* Hottest temperatures in Hawaii and what year it occurred
* Average rainfall amount from different parts of Hawaii
* Average temperatures in Hawaii by month
* Average wave height in Hawaii by month
* Top 10 countries that import to Hawaii
* Top crop items imported to Hawaii

#### Instructions

1.  Create a project folder called `basic-data-viz-project`
2.  Inside of the folder create a file called `main.py`
3.  Open `main.py` in your code editor
4.  Import the `pygal` package at the top of your file
5.  Create a chart of your choice with the pygal library
6.  Add a title to your chart
7.  Add your data to the chart using the `.add()` method provided by pygal to your chart variable name
8.  In order for your chart to display in the browser you will need to attach the `.render_in_browser()` method provided by lxml to your chart variable name
