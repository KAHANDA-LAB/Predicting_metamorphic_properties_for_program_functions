# Predicting metamorphic properties for program functions

The 5 files with the name \*FinalLabel.txt contain 100 rows each. Each row corresponds to 100 program functions and their label separted by a space. 

The name of the file is a ceratin metmorphic property (see https://onlinelibrary.wiley.com/doi/abs/10.1002/stvr.1594). Following is the first few lines from perClassLabelFinal1.txt. It is based on the permutative property. For example, "min" is the name of the function that finds the minimum value in a given list of numbers. 1 indicates that is program has the permutative property (hence labeled "positive"). 0 indicates negative.

min:1 \n
max:1 \n
covariance:0 \n
...

The location.txt file provides the web resources that can be used to obtain the javadoc for 2/3 of the above programs. For example, "min" can be found by visting https://dst.lbl.gov/ACSSoftware/colt/api/cern/jet/stat/Descriptive.html and searching for "min". You are welcome to find javadoc for other programs (or not use them).
