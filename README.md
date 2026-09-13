# Customer Support Ticket Analyser

## Project Overview

The **Customer Support Ticket Analyser** is a Python-based project designed to store, clean, and analyse customer support ticket data.

The project demonstrates the use of **Python dictionaries, lists, loops, functions, string methods, sets, and basic data analysis** to extract useful insights from customer support tickets.

## Objectives

* Store customer support ticket information.
* Add new tickets dynamically.
* Validate ticket priorities.
* Clean and standardize issue descriptions.
* Analyse tickets using keyword-based searches.
* Analyse ticket priorities.
* Identify the ticket with the longest issue description.
* Extract and sort unique words from ticket descriptions.
* Derive meaningful insights from customer support data.

## Technologies Used

* **Python**
* **Jupyter Notebook / Google Colab**
* **Git & GitHub**

## Project Tasks

### Step 1: Preloaded Tickets

The project begins with a dictionary containing 10 preloaded customer support tickets.

Each ticket contains:

* Ticket Number
* Customer Name
* Issue Description
* Priority

The initial ticket data is displayed in a readable format.

### Step 2: Add More Tickets

Users can add new customer support tickets by entering:

* Customer Name
* Issue Description
* Priority

The system:

* Automatically generates ticket numbers starting from **11**.
* Accepts only **High, Medium, or Low** priority.
* Appends the new ticket details to the existing data.

### Step 3: Text Cleaning

All issue descriptions are cleaned and standardized using Python string methods.

The cleaning process includes:

* Removing punctuation such as `. , ! ? -`
* Converting multiple spaces into a single space
* Removing leading and trailing spaces
* Converting text to lowercase
* Replacing shorthand such as `ok` with `okay`

### Step 4: Keyword-Based Issue Insights

A function named `count_tickets_with_word()` is created to count the number of tickets containing a specific keyword.

The analysis checks the following keywords:

* **poor**
* **good**
* **slow**
* **excellent**

The keyword search is case-insensitive.

### Step 5: Final Summary & Insights

The final analysis includes:

#### 1. Final Cleaned Ticket Data

Displays the complete cleaned `ticket_data` dictionary in a readable format.

#### 2. Priority Analysis

Calculates the number of:

* High-priority tickets
* Medium-priority tickets
* Low-priority tickets

#### 3. Longest Issue Description

Identifies the ticket with the highest word count and displays:

* Ticket Number
* Customer Name
* Cleaned Issue Description
* Word Count

#### 4. Unique Words

A set is used to extract all unique words from the issue descriptions.

The result displays:

* Total number of unique words
* Sorted list of unique words

## Key Insights

The project summarizes customer support tickets by analysing priority levels, keyword frequency, and unique words to understand the overall ticket pattern. It examines keywords such as **poor, slow, good, and excellent** to identify customer complaints and service quality issues. The observed patterns can help anticipate recurring issues and high-priority tickets. Based on these insights, support teams can prioritize urgent tickets, improve service quality, and address recurring customer concerns.

## Python Concepts Demonstrated

This project demonstrates the following Python concepts:

* Dictionaries
* Lists
* `for` loops
* `while` loops
* Functions
* Conditional statements
* String methods
* `.replace()`
* `.split()`
* `' '.join()`
* `.strip()`
* `.lower()`
* Sets
* `len()`
* `max()`
* `sorted()`
* List indexing
* User input and validation

## Project Workflow

```text
Preloaded Ticket Data
        ↓
Add New Tickets
        ↓
Validate Priority
        ↓
Clean Issue Descriptions
        ↓
Keyword Analysis
        ↓
Priority Analysis
        ↓
Find Longest Issue
        ↓
Extract Unique Words
        ↓
Generate Customer Support Insights
```

## Expected Outcome

The completed Ticket Analysis System provides a structured way to manage and analyse customer support data. It helps identify common keywords, understand ticket priorities, find detailed customer issues, and extract unique vocabulary from customer feedback.

## Conclusion

This project demonstrates how Python can be used for **data cleaning, text processing, validation, and exploratory analysis** of customer support ticket data. The analysis provides useful insights that can help support teams improve service quality, prioritize customer issues, and identify areas for improvement.

## Created by Suganya
## Aspiring Data Analyst
