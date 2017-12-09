# BinPackaging
My attempt at implementing 3D Bin Packaging logic using the First Fit Decreasing Strategy

The code is written to run on a windows machine. I used Dask to parallelize the code and create multiple processes 
depending on the number of cores of your machine. 

Steps to run this

1. Copy the contents of the repo on to your local
2. Make sure the python packages are installed
3. Run the Run.py file with two parameters - Filepath of the Order Data and the filepath of the Results (should be an excel file)
4. The code would run and creates a results excel file in the folder based on the filepath you provide


