This code was made as a project for the Free Code Camp course: Data Analysis with Python.
https://www.freecodecamp.org/learn/data-analysis-with-python/

## function: def calculate_demographic_data(print_data=True):

This function uses the Pandas library to analyze a demographic dataset and extract key socioeconomic statistics.

It reads data from a CSV file and calculates various metrics, such as the racial distribution of the population, the average age of men, and the overall percentage of people with a Bachelor's degree. A major focus of the function is analyzing income thresholds (specifically, earning more than $50K a year) across different groups. It determines the percentage of high earners based on their education level—comparing those with advanced degrees to those without—and evaluates the earnings of individuals who work the absolute minimum number of hours per week.

Additionally, it identifies the country with the highest proportion of high earners and finds the most common occupation among high-earning individuals in India. Finally, the function optionally prints these insights to the console and returns all the calculated variables packaged inside a dictionary for further use.