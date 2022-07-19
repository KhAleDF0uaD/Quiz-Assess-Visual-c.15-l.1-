Gather

import zipfile
import pandas as pd

with zipfile.ZipFile('armenian-online-job-postings.zip', 'r') as myzip:
    myzip.extractall()

# Read CSV (comma-separated) file into DataFrame
df = pd.read_csv('online-job-postings.csv')

Assess

df

    Missing values (NaN)
    StartDate inconsistencies (ASAP)
