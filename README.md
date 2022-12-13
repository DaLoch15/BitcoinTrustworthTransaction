# BitcoinTrustworthyTransactionProject

# Link to Presentation
https://drive.google.com/file/d/1mMAHEfoFTfBETIOpqqsAUSh_jrWa38iv/view?usp=share_link 

# Project Summary
Our proposed final project was to create a class representing a bitcoin network and given two users and some conditions, ouptut a path/result.

# Code
All code files can be found in the code/ directory. To run the code:

1. Run cmake .. in the build directory. 
2. Then make main within the build directory.
3. Run ./main in the terminal and insert two integers in the command line representing the start and end user. A sample input looks like this, ./main 1 734
4. To run our test cases, make test within the build directory and run ./test in the terminal. The tests that we have created are unit tests for each of the major functions within our BitcoinNetwork class. The test cases cover reading in the csv file, whether or not there is a path between two nodes, the number of strongly connected components within a graph, and the shortest path (most trustworthy) betweens two users.

# Data
Our test data was taken using Stanford Large Network Dataset Collection. It is Bitcoin OTC trust weighted signed network. The link is attached here: http://snap.stanford.edu/data/soc-sign-bitcoin-otc.html.

# Documents
Our signed contract, proposal, and development logs can be found in the documents/ directory.

