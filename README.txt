TOPSIS:
Technique for Order Preference by Similarity to Ideal Solution (TOPSIS) is a multi-criteria decision making method. 
The method is based on finding an ideal and an anti-ideal solution and comparing the distance of each one of the alternatives to those.
TOPSIS chooses the alternative of shortest Euclidean distance from the ideal solution, and greatest distance from the negative-ideal solution.

Package Usage:
To install the package:
pip install TOPSIS-Tanisha-101803042
This is a package focusing on finding the topsis score and rank of a dataframe with only numerical values.

Command Prompt Usage :
>>TOPSIS-Tanisha-101803042.topsis "inputfile.csv" "1,1,1,2" "+,+,+,-" "result.csv"

Python IDLE:
>>> import pandas as pd
>>> import TOPSIS-Tanisha-101803042.topsis
>>> dataset = pd.read_csv('inputfile.csv').values
>>> d = dataset[:,1:]
>>> w = [1,1,1,1]
>>> im = ["+" , "+" , "-" , "+" ]
>>> TOPSIS-Tanisha-101803042.topsis(d,w,im)
