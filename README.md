# Heart Rate Prediction
This repository aims to develop a program that predicts heart rate for cyclists using artificial intelligence tools. By leveraging a dataset of training files with various variables, including heart rate, the program seeks to provide accurate heart rate estimates for files lacking this information.


## ROADMAP: PENDING TASKS

- **Convert data from .fit to .csv**  
  - Export files from:  
    - Strava (.fit directly)  
    - TrainingPeaks (.gz, decompress using .7zip)  
    - Garmin Connect (folder containing .fit files)  
  - Use Garmin Connect's **fitSDK** tool for file conversion:  
    - **Java**: Run `FitToCSV.bat` (drag and drop the .fit file to generate the .csv file)  

- **Build our .fit activity database**  
  - Collect approximately 50 .fit files and 10 test files  

- **Adapt data to our model**  

- **Run the model**  

