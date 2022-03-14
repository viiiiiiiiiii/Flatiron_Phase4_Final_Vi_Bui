# Flatiron Phase 4 - Final Project by Vi Bui
# Movie Recommendation System

<img src='Images/Popular_Movies.png'>

# Overview

Vi(sion) Studios, a new streaming service, is looking to launch a concept called "Digital Cinema Night" where customers can build a "Cinema Night" around specific movies. They've hired us to build a Recommendation System in order to launch this concept.  

## Data, Methodology, and Analysis <br/> 

Data source: MovieLens data which captures Movies, Ratings, Genres, and Year. For this analysis, we used all metrics available with the exception of Tags which may be used for later analysis.  

From MovieLens: “Users were selected at random for inclusion. All selected users had rated at least 20 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.”

Data: 9724 unique entries and 610 unique users 

**Models Built:** 

1. Singular Vector Decomposition Model (SVD)
2. k-Nearest Neighbor Baseline Model (KNNB)
3. Non-Negative Matrix Factorization Model (NMF)

**Features included and created:**
1. Movie ID (included)
2. User ID (included) 
3. Ratings (included)
4. Year (cleaned & created)
5. Genre (cleaned & created) 
6. Ratings Count (created) 

<br>

## BUSINESS VALUE
<img src='Images/Business_Value.png'>


## OBSERVATIONS ABOUT THE DATA
### The data is skewed: 
- 69% Male
- 76% Major/Discipline - STEM

<img src='images/DS_Gender.png'>

<img src='images/DS_Major.png'>


<br>

### Most participants trained for 50 hours or less and about 25% changed jobs

<img src='images/DS_Training_Hours.png'>

<img src='images/DS_Career_Change.png'>

<br>

# Models & Metrics 
## We ran various models and chose the model with the highest recall rate 

- Because there is a smaller portion of participants who changed jobs (25%), the metric we used to measure our models' performances was Recall 

- Recall measures the % a model predicts True Positives (employees "Looking for a Job Change") that actually are looking for a job change

- Our model is expected to predict True Positives (i.e. predict employees "Looking for a Job Change" that are actually looking for a job change) 77% of the time


<img src='images/Model_Results.png'>

## THE MOST IMPORTANT DETERMINANT OF JOB CHANGE IS CITY DEVELOPMENT INDEX
### Other important features (some which also ranked high in other models are): 
- Experience 
- Small company size (<10 to 500)
- Education level: Graduate Degree


 ## **CONCLUSIONS** 
- While this data gives us insight into the importance of location, company size, education, and experience in identifying those looking to change jobs, there are endless ways to use this data to help RADs build a future for Data Scientists

## **FUTURE WORK**
- Identify recruiting opportunities and strategies for RADs’ Data Science program (recruit more females; recruit 'unlikely' candidates that do not have a background in STEM; recruit in various cities)
- Offer another round of Data Science training curriculum to engage more employees 
- Gather more data following Round 2 and re-run models
- Continue refining overall process and models
- Make sure all who want to explore Data Science have the opportunity! 


# Repository Structure

- images 
- README.me
- Vi_Bui_Phase3_Project_FINAL_FINAL.ipynb
- Vi_Bui_Phase3_Project_FINAL_FINAL - Jupyter Notebook.pdf
- Vi_Bui_Phase3_Project_FINAL_FINAL_PresentationPDF.pdf
- Flatiron_Phase3_Final_Vi_Bui/edit/main/README.md.pdf
