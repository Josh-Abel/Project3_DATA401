This is the README file for the DATA 401 Project 2 created by Josh Abel, Arman Rafian Chan, and Steven Taruc.

To run our program the only file that needs to be run is `Project3_Group3.ipynb`. 
The first part of the file is a cell which contains our class implementation to the neural network.
Then, the file downloads the data (you must be in a directory so the path to the data is reached, if not you must change the path when reading the CSV in the cell right below the "Feature Selection" section). 
Next, the file tranforms the data as described in the report. Note that this transformation saves two CSVs into the current working directory, one for the imputed data, and one for the final dataframe, as this can be referenced for later use if needed.
After that, we run our data on a scikit-learn linear regressor.
Finaly, we run our data on the neural network that we implemented.