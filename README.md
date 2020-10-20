# MP-Neuron

# About
One Fourth Labs is an IIT Madras incubated startup with a goal to make India ready for the AI age. TO skill Indian workforce in the areas of Artificial Intelligence (AI) at almost one-tenth the industry upskilling price.

PadhAI provides India-specific courses on AI, and is open to all students, faculty, and professionals with a basic background in mathematics and python

# Task
The goal is to identify the people's opinion on mobile phones using MP Neuron. The data points are scraped from 91mobiles.com

Evaluation Metric
Submissions are evaluated on **Accuracy Score** between the predicted and the actual labels on test dataset

# File descriptions
train.csv - The training set.
There are 355 rows with 99 columns.
The first column 'PhoneId' is the unique identifier for each phone.
The last column 'Rating' is used as the indicator of peoples' opinion. If the 'Rating' of a mobile >= THRESHOLD (4), then the user LIKES (1) it, otherwise NOT (0).

Path in Kaggle Kernel: "../input/train.csv"

# test.csv - The test set.
There are 119 rows with 98 columns.
The first column 'PhoneId' is the unique identifier for each phone.
Use this data to test your model and make submission in the 'sample_submission.csv' file format.

Path in Kaggle Kernel: "../input/test.csv"

# sample_submission.csv - The sample submission file, where all the rows are assigned with class 1.
There are 119 rows with 2 columns.
Path in Kaggle Kernel: "../input/sample_submission.csv"
