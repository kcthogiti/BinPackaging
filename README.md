# BinPackaging
My attempt at implementing 3D Bin Packaging logic using the First Fit Decreasing Strategy

The code is written to run on a windows machine. I used Dask to parallelize the code which would create multiple processes 
depending on the number of cores of your machine. 

Data.xlsx has two tabs. 
1. Order Data - Shows the order data. Each order can have multiple lines (items). The dimensions of items are also present in this tabs
2. Boxes - Shows the available box sizes to be used for the analysis

Steps to run this

1. Copy the contents of the repo on to your local
2. Make sure the python packages are installed
3. Prepare your order data file similar to the one in the repo (Data.xlsx) 
3. Run the Run.py file with two parameters - Filepath of the Order Data and the filepath of the Results (should be an excel file)
4. The code would run and creates a results excel file in the folder based on the filepath you provide


