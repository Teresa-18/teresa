# OUR PROJECT REPO
# Dependencies and Setup
import matplotlib.pyplot as plt
import pandas as pd
import numpy as np
import scipy.stats as st
# Study data files
RMS_path = "Downloads/RMS.csv"
# Read the data
RMS = pd.read_csv(RMS_path)
print(RMS.head())

## MAJOR FINDINGS
1. Are types of crimes more prevalent in one area of San Antonio versus another?
    Top 10 zip codes for arrests are 78205, 78207, 78201, 78228, 78216, 78223, 78227, 78213, 78210, 78237.
    drug and alcohol violations are the most prevalent

2. Are there any identifiable crime trends annually or monthly? 
    There was little to no significant variation in the types of arrests either by month or year.
    drug and alcohol violations are the most prevalent
    
3. What age group has the highest amount of offenders and what types of crimes do they commit?
    The age group with the highest arrests were the 20-29 year olds.

