# **Assignment 4 - Data versioning with DVC**

To track data using **DVC** and store it in a remote storage (Virtual Machine).

In this task you will version the dataset to ensure reproducibility.

---

## Steps to complete the task

---



###  **1. Log in to your VM and create a new directory to act as remote storage**

## Step1 completed

### **2. Create a python virtual environment, and activate it**

## Step2 completed

### **3. Install DVC and Initialize a DVC repository**
 
### **4. Configure Remote Storage (Directory present on VM)**


### **5. Track the main data using DVC**
- Track the main data(data/data_main.csv) using DVC.
- Tag it as v1.


### **6.Add Monthly Data (month1_data.csv, month2_data.csv) Progressively**
- Update the main data by running the `data_aggregator.py` file.

- Note: By default `data_aggregator.py` will add month2_data.csv to main data. To add month3_data.csv, change the path of dataset2 in in the `data_aggregator.py` file.

- After running the file to add the monthly data (e.g., month2_data.csv and month3_data.csv), track and push these changes using DVC. Tag them as v2 and v3 respectively.


### 6. Upload Screenshots
- Take screenshots of each command and its output to show how the data is tracked, added, and pushed to remote storage.
- Create a folder named "Screenshots" in the repository and upload the screenshots.

## Notes
- commit the changes in the codespaces to submit your repo.
- To know more about the data used in this assignment: https://archive.ics.uci.edu/dataset/222/bank+marketing
- Use dvc status to check the tracking status of your files.
