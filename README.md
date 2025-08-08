# CSV-File-read-code-
#The program is for only read .csv files

import pandas as pd

filepath = input("Enter the path of the CSV file:")

dataframe = pd.read_csv(filepath)

print("Your Dataframe....\n", dataframe)
