# Bikes EDA
Bikes EDA is a practice project performing Exploratory Data Analysis on some example bike usage data based on train timing. This project is to learn and understand different data analytic techniques to gain insight from a raw data.

## Packages Used
This project uses the following python libraries for data analysis
* Python 3
* Pandas Profiling
* Numpy
* Pandas
* Matplotlib

## Clone the project
The packages used in the project are installed in a python virtual environment to avoid conflicts with existing packages. Follow the steps to clone and run the project in jupyter notebook
```
git clone https://github.com/rama-2402/bikes-eda.git
cd bikes-eda/
```
After navigating to the project directory, Create a virtual environment and install the packges using the following commands.
```
python3 -m venv venv/

#If you are using bash shell 
source venv/bin/activate 

#If you are using Fish shell
source venv/bin/activate.fish

#To install the necessary dependencies
pip install -r requirements.txt 

#To run the jupyter notebook 
jupyter notebook
```
## Troubleshooting
```
#Nuke the environment
rm -r venv/

#Install a new environment and dependencies
python3 -m venv venv/                 
pip install -r requirements.txt 
```

## Analysis
Following analysis has been made on the sales data
* Exploring the dataset to look for outliers
* Finding the correlation between different data values using graphs and charts of Matplotlib


#### CREDITS
The data for this exploratory analysis has been taken from the materials provided iNeuron Intelligence. The exploratory analysis was done in my point of view using different approach.
