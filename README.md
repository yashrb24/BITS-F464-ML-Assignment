# BITS-F464-ML-Assignment

### Name: Yash Bhisikar
### ID: 2021A7PS0483G


## Project Structure
- `csv_files`: contains all the `.csv` files. For Kaggle Submission, I could only keep 1 `.csv` file, otherwise it was throwing an error. Keep the `train.csv` and `test.csv` files in this folder before executing the main notebook. In the quanta submission, I have the `test.csv` file in the folder.  
- `figures`: contains all the plots mentioned in the report
- `weights`: contains all the different model weights I saved while training. Some of them belong to different model structures which I haven't documented in the report, but are saved for future work
- `notebooks`: contains jupyter notebooks for different experiments included in the report. The experiment performed can be identified from the title of the notebook. Also contains `eda.ipynb` and `playground.ipynb` where I did exploratory analysis and messing around with models, respectively. 
- `2021A7PS0483G_psc.ipynb`: notebook which generates `submission.csv` for Kaggle. Just using `Run All` option on the notebook cells should suffice. The file will be saved to `csv_files` folder
- `2021A7PS0483G_report.pdf`: The Assignment report
- `requirements.txt`: Contains all the dependencies required to run any notebook in this project 
