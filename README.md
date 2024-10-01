# ENG-220-MATLAB-PROJECTS

Part A: Setup and Initialization
In Part A of the Matlab project, we started by taking a specific portion of data from an excel file and saving it as a workspace file. This step sets up the data for further analysis in Part B. The process involves:

Loading the Excel File: Importing the Excel file into Matlab.

Saving to Workspace: Save the imported data as a .mat file using the save function. This file will be used in later parts of the project.

Displaying Information: Use commands like "disp" to display information about the data in the command window. This includes explaining the structure of the data, such as the number of rows and columns, and any other details about the dataset.

Text Display: The final command in this part involves displaying a custom message in the command window. This is done using the disp function with a string argument, which prints the text enclosed in quotation marks.

--------------------

Part B: Analyzing Class Scores
In Part B we build off of the data prepared in Part A. Here, we perform a new analysis on the class scores imported from the excel file. This analysis includes:

Workspace File Setup: Loading the .mat file created in Part A.

Data Analysis: Perform a series of calculations and analyses on the data. This includes:

- Class Average: Calculate the average score of the entire class.
- Grade Average: Compute the average score for each grade category.
- Individual Scores: Extract and display individual student scores.

Modifying the Code: To focus on specific data, modify the code by changing references from "col11" to "col1". This adjustment ensures that only the last column of data is considered in the analysis.

Graphical Representation: Generate graphs to visualize the results. After modifying the code, rerun it to produce updated graphs that reflect the final grade average and final class average.
