# ACCENTURE SOCIAL BUZZ DATA ANALYSIS

Task 1 - Data Exploration and Preprocessing

Introduction:-

Social Buzz emphasizes content by keeping all users anonymous,only tracking user reactions on every piece of content. There are many ways that users can react to content, spanning beyond the traditional reactions of likes, dislikes, and comments.This project focusing on analyzing popular content and type of contents.

## Dependencies

Using Following external libraries are required to run the Jupyter Notebook:

Pandas,
Numpy,
Matplotlib,
seaborn


## Setup Instructions:

Open the Jupyter Notebook:
Launch the Jupyter Notebook application using this command.

Install Dependencies:
installs the required Python libraries.

Load The different Data Sets:
Loading the data sets in Jupyter Notebook.

Run the Cell in Jypiter Notebook:-
(commonly Shift + Enter) used for the Running a cell in Jypiter Notebook.

## Usage

Selecting the required 3 Datasets (`Content.csv` , `Reactions.csv` , `ReactionType.csv`) form the all 7 Datasets from the client.
following the instructions witin Notebook to Load the Data and interepting the result.

## Schema Mapping Explanation:

1. Loading Data:
Utilizes pandas to load the datasets.

2. Data Cleaning:
Before go through the Analysis of the data, using some `info` and `describe` mehtod to understand the data structure.

First part of analysis in data Cleaning i remove the missing values from the All the 3 data sets by using `dropna` method and remove the unnecessery Columns.
convert Date column into Datetime column to fetch Month from the Date.

Finding the Top 5 Categories according to the Score , Best Month for the Popular Content. Export the Required files to share with the client.

3. Visual Analysis on The Dataset:
Using `matpolotlib` & `seaborn` getting some interesting insights from the Data. There are 3 Graphs to get the better undestand the inights from the Data.

#### Top 5 Popular Categories Vs Total Score

#### Popular Content Type Vs Total Score

#### Popular Content Type Vs Month


4. Output Results:
#### From Graph : Top 5 Popular Categories Vs Total-Score :- 

Animals
Science
Healthy eating
Technology
Food

Animals has the Popular Categories.

#### from Graph : Popular Content Type Vs Total Score:-

PHOTO
VIDEO
GIF
AUDIO

PHOTO is the most Popular Content Type.

#### from Graph: Popular Content Type Vs Days:-

Number of Popular content increase on Weekends (Saturday , Sunday)

---
Contributor: Vinay Mudgal
Contact: insightfulvinay@gmail.com
Date: February 7, 2024
---
