# CPAD

CPAD stands for Computer-generated plus-shape architectural designs. It is written in computer language Processing.

Given a set of data (number of rooms, area of each room, adjacency relation among the rooms given in terms of weighted adjacency matrix), CPAD generates a plus shape floor plan and its adjacency graph. Other shape floor plans can also be generated by making small changes in the code.

The plus-shape floor plans are generated by adjoining 5 different rectangular blocks. These rectangular blocks are formed on the basis of weighted adjacency matrix and they are one of the best connected arrangements of rectangular pieces inside a rectangle.

By making small changes in the input.txt file, about 4 million different plus shape floor plans can be generated for a given set of data. Therefore, for the classification of obtained solutions, CPAD computes some graph covariants which can be found in output.txt file.

The following libraries are required to run the code.
Jama
jgrapht
gicentreUtils

