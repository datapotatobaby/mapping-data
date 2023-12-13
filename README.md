# Exercises in Loading, Manipulating, and Saving JSON Data in Python and Pandas

This exercise is part of the Coursera course: [Python, Bash and SQL Essentials for Data Engineering Specialization](https://www.coursera.org/specializations/python-bash-sql-data-engineering-duke)

## My Tasks ## 
Fork the Github repository and use the `exercise.ipynb` Jupyter Notebook that has pre-loaded starting points.

The Jupyter Notebook has already preloaded the CSV file with examples on how to use it with Pandas or a Dictionary with the csv module.

1. Use a distinct field to retrieve data, like:

- Type of wine (red or white)

- Wine score range or baseline (e.g. between 90 and 92 points)

- Region

2. Capture every row that matches your condition, and after processing, save everything to a formatted new JSON file

3. Create a Demo project in GitHub with a README.md that describes what you did.

4. Create a Demo Video and reference it in your GitHub Project.

## My Responses to the Tasks ##

You can follow along with my work in the `excercise.ipynb` Jupyter Notebook.
I have added my work and explorations, along with commentary there. 


There's so much that we can do with Python's Pandas library for data manipulation. But, I'd like to explore some library-independent solutions to the tasks first. Then we will do it again with Pandas.

## Filtering Without Pandas, and Writing to JSON

**My Goals**
1. Work with filtering text 
    - Create a dictionary of white wines from the wine ratings csv. 
    - Save it as a new JSON file.
2. Work with filtering numbers
    - Create a dictionary of wines ranked above 96 points. 
    - Save it as a new JSON file.

## Filtering Using Pandas, and Writing to JSON

1. Filter the dataframe to show us only Rose wines. 
2. Convert it to a dictionary type using `df.to_dict()`.
3. Save the dictionary to a JSON file.
4. Go further and explore the data even more, seeing if there's any improvements that can be made on the dataset according to my own experience in the wine industry.

### Questions or Issues?
Please use the [Issues](/../../issues) tab to report any issues or ask questions. Any feedback is welcome!
