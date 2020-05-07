# OBD2_driver_identify

This is Masters thesis project "Driver identification using OBD2 data."
Link to research: https://www.researchgate.net/publication/341132146_Driver_identification_using_OBD2_data

This is python code used to identify driver identity using unsupervised classification algorithms (u-shapelet and k-means)
from real data collected from vehicle (Mitsubishi COLT) sensors using OBD2 standard in uncontrolled environment.

driver_data/ 
  contains data collected from 4 drivers.

notebook_files/ 
  contains code for unsupervised classification. Python code in Jupiter notebooks.

notebook_files/dataFunc.ipynb
  data cleaning and preparation
  
notebook_files/u-shaplet.ipynb
  finding unique shapelets describing drivers
  
notebook_files/k-means.ipynb
  using k-means to analyze results of u-shaplet algorithm to find most probable driver count
