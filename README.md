# Problem set: Jupyter, pyplot and numpy

## Introduction
These problems relate to Jupyter, numpy, and pyplot. We will use the famous iris data set. 

## Assignment Specification

__1. Get and load the data__

Search online for Fisher’s iris data set, find a copy of the data, download it and save it to your repository. If it is not in CSV format, use whatever means (Excel, notepad++, visual studio code, python) to convert it to CSV and save the CSV version to your repository also. Open your Jupyter notebook for this problem sheet, creating a new one if needed, and load the CSV file into a numpy array.

__2. Write a note about the data set__

In a markdown cell at the start of your notebook, write a short description of the iris data set, complete with references.

__3. Create a simple plot__

The dataset contains five variables: sepal length, sepal width, petal length, petal width, and species. Use pyplot to create a scatter plot of sepal length on the x-axis versus sepal width on the y-axis. Add axis labels and a title to the plot.

__4. Create a more complex plot__

Re-create the above plot, but this time plot the setosa data points in red, the versicolor data point in green, and the virginica data points in blue. Setosa, versicolor, and virginica are the three possible values of the species variable. Add a legend to the plot showing which species is in which colour.

__5. Use seaborn__

Use the seaborn library to create a scatterplot matrix of all five variables.

__6. Fit a line__

Fit a straight line to the variables petal length and petal width for the whole data set. Plot the data points in a scatter plot with the best fit line shown.

__7. Calculate the R-squared value__

Calculate the R-squared value for your line above.

__8. Fit another line__

Use numpy to select only the data points where species is setosa. Fit a straight line to the variables petal length and petal width. Plot the data points in a scatter plot with the best fit line shown.

__9. Calculate the R-squared value__

Calculate the R-squared value for your line above.

__10. Use gradient descent__

Use gradient descent to approximate the best fit line for the petal length and petal width setosa values. Compare the outputs to your calculations above.

## How to clone this repository

* In the Clone with HTTPs section, copy the clone URL for the repository.
* Open Git Bash.
* Change the current working directory to the location where you want the cloned directory to be made.
* Type `git clone`, and then paste the URL you copied in Step 2.
* Press Enter. Your local clone will be created.

## How to open the jupyter notebook
The Jupyter Notebook App can be launched by clicking on the Jupyter Notebook icon installed by Anaconda in the start menu (Windows) or by typing in a terminal (cmd on Windows):

`jupyter notebook`

This will launch a new browser window (or a new tab) showing the Notebook Dashboard, a sort of control panel that allows (among other things) to select which notebook to open.

Look for the folder which you have previously cloned named `python-problems` - open it and click on `iris-dataset.ipynb`
