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

**Congratulations**
You have successfully set up Python, installed Jupyter Notebook, and run your first Machine Learning program.



**Other Option:-**
Running First Machine Learning Program on Google Colab

Google Colab is a **free online platform by Google** that provides:  
- A Jupyter Notebook environment in your browser  
- Pre-installed ML libraries (numpy, pandas, matplotlib, scikit-learn, etc.)  
- Free CPU and GPU support for faster execution  

## Step 1: Open Google Colab

1. Go to [https://colab.research.google.com](https://colab.research.google.com)  
2. Sign in with your **Google Account**  

## Step 2: Upload the Notebook

You have two options:  

## Option A: Open from GitHub
1. In Colab, click **File → Open Notebook → GitHub tab**  
2. Enter your repository link, e.g.:  
https://github.com/rushikeshhadawale/ML-Lab.git

yaml
Copy code
3. Select the file `first_ml_program.ipynb` → Click **Open**  

##Option B: Upload from Local Machine
1. In Colab, click **File → Upload Notebook**  
2. Upload your `.ipynb` file (downloaded from this repo).  

##Step 3: Check Dependencies

Most required libraries (numpy, pandas, matplotlib, scikit-learn) are already installed.  

If you need extra packages, run in a cell:
```python
!pip install package_name
Example:

python
Copy code
!pip install seaborn

Step 4: Run the Notebook
Click Runtime → Run all to execute the entire notebook

Or run cells one by one with Shift + Enter

Outputs (numbers, tables, graphs) will appear below each cell.

Step 5: Save Your Work
To save changes to Google Drive → File → Save a copy in Drive

To download your notebook → File → Download → Download .ipynb

Advantages of Colab
No installation required (Python & Jupyter already set up)

Free access to GPU/TPU (helpful for deep learning)

Easy sharing & collaboration (just like Google Docs)

Congratulations
You have successfully run your first ML program on Google Colab! 

