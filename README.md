# Data Analytics Project - UTK INSC 486
## Team: Ronak Karuhatty, Manav Patel, Kirtan Patel

## Project Overview
Analyzing student academic performance using the UCI 
Predict Students Dropout and Academic Success dataset 
to identify key factors that influence student outcomes.
The goal is to identify key factors that influence whether 
a student Graduates, Drops Out, or remains Enrolled.

## Prerequisites - Install These First

### 1. Install VS Code
Download and install VS Code from:
https://code.visualstudio.com/download

### 2. Install Python
Download and install Python 3.13.7 from:
https://www.python.org/downloads/
During installation check the box that says "Add Python to PATH"

### 3. Install VS Code Extensions
Open VS Code and install these two extensions:
- Python (by Microsoft)
- Jupyter (by Microsoft)
To install: click the Extensions icon on the left sidebar 
and search for each one

## Setup Instructions

### 4. Clone the repository
Open your terminal and run:
git clone https://github.com/RonKar17/data-analytics-project-utk.git

### 5. Open the project
In VS Code go to File > Open Folder and select the cloned folder

### 6. Create and activate virtual environment
Open the VS Code terminal and run:
python -m venv venv
source venv/bin/activate
You should see (venv) appear at the start of your terminal line

### 7. Install required libraries
pip install pandas matplotlib seaborn scikit-learn jupyter

### 8. Open and run the notebook
Open notebooks/exploration.ipynb in VS Code
Select the venv kernel when prompted
Run all cells to see the full analysis

## Project Structure
- data/ - contains the dataset (already included)
- notebooks/ - contains the Jupyter notebooks

## Contributing
After making changes run the following lines one at a time:
git add .
git commit -m "description of your changes"
git push origin main

To get your teammates latest changes run:
git pull origin main
