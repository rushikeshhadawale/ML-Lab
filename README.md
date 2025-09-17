# ML-Lab
Machine Learning Lab
# First Machine Learning Program

This repository contains my **Machine Learning program** implemented in Python.  
The program is written inside a **Jupyter Notebook**, which allows you to run code step by step and see the results interactively.  

## Step 1: Install Python

1. Go to the official Python website: [https://www.python.org/downloads/](https://www.python.org/downloads/)  
2. Download the latest stable version (Python 3.x).  
3. During installation, **check the option "Add Python to PATH"** → this allows Python to be used from Command Prompt (CMD).  
4. Verify installation by running in CMD:
5. 
   ```bash
   python --version
You should see something like:

nginx
Copy code
Python 3.11.5

Step 2: Install pip (Python package manager)
Pip usually comes with Python, but to make sure it’s updated, run:

bash
Copy code
python -m ensurepip --upgrade
python -m pip install --upgrade pip
This ensures you can install external libraries (like numpy, pandas, etc.).

Step 3: Install Jupyter Notebook
Jupyter Notebook is the tool you’ll use to run your ML program.

Install it using pip:

bash
Copy code
pip install notebook
To check if it installed correctly:

bash
Copy code
jupyter --version

Step 4: Install Required ML Libraries
Most ML programs need common Python libraries. Install them with:

bash
Copy code
pip install numpy pandas matplotlib scikit-learn
numpy → for mathematical operations

pandas → for handling datasets
matplotlib → for visualization (graphs & plots)
scikit-learn → for machine learning algorithms

Step 5: Open the Repository Folder
Download or clone this repository:

bash
Copy code
git clone https://github.com/rushikeshhadawale/ML-Lab.git
Or simply download as a ZIP and extract it.

Navigate into the project folder:

bash
Copy code
cd path\to\your\repository

Step 6: Start Jupyter Notebook
In CMD, run:

bash
Copy code
jupyter notebook
This will open a new tab in your default browser.

You will see a file explorer view of your project folder.

Step 7: Run the ML Notebook
Click on the file first_ml_program.ipynb (or your .ipynb file).

The notebook will open in the browser.

Run the cells one by one:

Select a cell → Press Shift + Enter to execute.

Outputs (numbers, graphs, results) will appear below each cell.

Troubleshooting
If Jupyter does not open, try:

bash
Copy code
python -m notebook
To stop Jupyter:

Go back to CMD window

Press Ctrl + C → then type y and press Enter.

Congratulations
You have successfully set up Python, installed Jupyter Notebook, and run your first Machine Learning program.
