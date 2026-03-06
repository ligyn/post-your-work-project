>**Note**: Please **fork** this Udacity repository so you have a **remote** repository in **your** GitHub account. Then you can clone the remote repository to your local machine. Later, as a part of the project, you will push your changes to the remote repository in your GitHub account.


# Bikeshare Data Analysis Project

This project is a command‑line data analysis tool designed to explore bikeshare usage data from several major cities. It loads a city’s dataset, optionally filters the data by month and day of the week, and then computes a variety of statistics—such as the most frequent travel times, the most popular stations, trip durations, and user demographics.

## Project Overview
The program guides the user through interactive prompts and analyzes bikeshare data using pandas and NumPy. After selecting filters, it loads the appropriate dataset and displays:

- Most frequent travel times
- Most popular stations and trips
- Trip duration statistics
- User demographics (user types, gender, birth years)

This project is ideal for learning about data filtering, aggregation, and user‑driven CLI applications in Python.

## How-To run the project

This project is designed to run in a Python environment (terminal or IDE). It interacts with the user, loads bikeshare CSV data, applies filters, and prints insights. Here’s how to use it step‑by‑step:

### Prepare the Required Files

Make sure the CSV files are in the same folder as the Python script:

```
example1.csv
example2.csv
example3.csv
```

These files contain bikeshare trip data used for analysis.

### Run the Script
In your terminal or IDE, run:

```
python bikeshare.py
```

_(assuming you named the file bikeshare.py)_

### Follow the On-Screen Prompts
The program will ask three questions:
a) Choose a city
You can type:

- example1
- example2
- example3

The script keeps asking until a valid city name is entered.

b) Choose a month filter
Type one of:

- january, february, march, april, may, june
- or all to avoid filtering by month

c) Choose a day-of-week filter
Type:

- monday, tuesday, … sunday
- or all to include every day

### View the Calculated Statistics
After loading and filtering the data, the program displays:


- Most frequent travel times: (most common month, day, hour)

- Popular stations and trips

- Trip durations: (total and average)

- User demographics: (user types, gender, birth years)

_Each section includes calculation time and is printed clearly for the user._

### Choose Whether to Restart
At the end, the program asks:

```
Would you like to restart? Enter yes or no.
```

Type **yes** to run another analysis
Type **no** to exit the program

## Contributing guidelines

Contributions are welcome. Use the comment section on GitHub.

## Date created

Created on March 2026.