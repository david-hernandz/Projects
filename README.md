# Jupyter Notebook Automation

For the 2024 Survey Hardware data, a binnable graph can be created using "Number of Students" which is the total number of rows on the Survey Hardware data (ie: each row represents a student who completed the Hardware survey).  

Graphs can be created using "Number of Students" for the following columns:\n
  A. Operating System
  B. CPU Cycle Rate (in GHz)
  C. CPU Number of Cores (int)
  D. RAM (in GB)
  E. Hard Drive Size (in GB)
  F. GPU Number of Cores (int)

Graphs cannot be created using "Number of Students" for the following columns:
  A. Timestamp - since there are many different timestamps for each student, the data does not present well in a graph
  B. GPU (short description as a string) - since there are many different descriptions, the data does not present well in a      graph.



