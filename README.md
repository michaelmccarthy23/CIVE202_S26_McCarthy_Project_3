# CIVE202_S26_McCarthy_Project_3
CIVE 202 Spring 2026 Project 3 - Visualization

1. Project Overview
The goal of this project is to analyse real world traffic behavior and trends using the NHTS and NGSIM datasets. The data was cleaned and grouped using a Jupyter notebook. A series of graphs was plotted using SNS and MatplotLib visualising trends and features primarily found in the NHTS Data. The NGSIM data was plotted using information from a specific lead and follower vehicle to provide a visual representation of their postion, speed, acceleration between each other to analyse follower vehicle dynamics. Then using the NGSIM information a simulated follower vehicle was created that only behaved based upon the leader vehicles information and a defined set or rules defined by the IDM Equations. This simulated follower vehicles behavior was then used a a comparison to the real world drivers behavior.

2. Procedures and information
   In order to run the Visualisation jupyter workbook you need to download the CIVE202_S26_McCarthy_Project_3.ipynb file labeled .ipynb and run it with Jupyter note book or other Python module. You will also need to download the NHTS and NGSIM data .csv files. Initalise the notebook and run the code line by line for it to function. You may need to update your version and/or download the latest numpy and matplotlib services.
   If you want to test or display another trajectory pair in the simulation you just need to edit selected trajectory pair "trajectory_number = ##"
This workbook is then repeatable for analysing or simulating different trajectory pairs.

3. Safety and Legal
   The Federal Highway Administration (FHWA) is the source and owner of the NGSIM and NHTS data.
   Be safe. 
