### Running instructions for linux environment
#### Prerequisite to have been installed.
**01.** Python3.6(Python3)  
**02.** Virtualenv  
**03.** Requirements that are in **requirements.txt**  
**04.** Extract data.tar.gz 

##### Step 01: Clone the project to your workplace
If you are using a ssh key for GitHub, please use flowing git command to clone the project.
```
git clone git@github.com:snandasena/stackoverflow-job-sat-stat-analyisis.git
``` 
Otherwise use HTTPS git method to clone the git repositories.  
```
git clone https://github.com/snandasena/stackoverflow-job-sat-stat-analyisis.git
```  
##### Step 02: Create a Python3.6(Python3) virtual environment inside the project root directory
Here I assumed you are in the project root directory and here **"."** is represent the current directory.  
```
virtualenv -p python3.6 .
``` 
Then activate the python virtual environment
```
source bin/active
```
##### Step 03: Install requirement that are in **requirements.txt** file.
Here is the command to Python requirements from a text file.
```
python -m pip install -r requirements.txt
```
##### Step 04: Running Jupyter notebook with Python virtual environments
```
jupyter notebook Stackoverflow_Job_Satisfaction_Statistical_Analysis.ipynb
```

[Link to Medium Blog](https://medium.com/@sajithnandasena/how-to-keep-employees-happy-in-the-it-industry-dda54249dbcc)
