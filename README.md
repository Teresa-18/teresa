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
