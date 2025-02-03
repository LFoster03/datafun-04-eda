# datafun-04-eda
## How to Install and Run the Project
I went into github and created a new public repo with a README file. I then went into my terminal and cloned my repo to my local machine.
    cd Projects -> git clone URL
Then I opened it in VS CODE.
    datafun-o4-eda code . 
I added the gitignore file by going to the root project folder and add file. 
I added the requirements.txt by going to the root project foler and add file.
I then pushed to my remote repository.
    '''git add . 
    git commit -m "message"
    git push'''
Then I added a .virtual environment.
    python3 -m venv .venv    
And activated it in the VS Code terminal.
    source .venv/bin/activate
Then git add, commit, and push. 
I then ran commands to install dependencies.
    '''source .venv/bin/activate
python3 -m pip install --upgrade pip setuptools wheel
python3 -m pip install -r requirements.txt'''
Then I added a new Python file titled demo.py.
Then I went to add a new file, choosing Jupyter and saved it as Practice-04.ipynb.

# Running the Project
I asked ChatGPT for different types of tasks you can do in Jupyter notebook and then picked a couple to do. The first task I chose was to analyze a list of numbers and then make it into a plot. 

# Import libraries
'''import numpy as np
import matplotlib.pyplot as plt'''

# List of numbers to analyze
[5, 7, 13, 17, 22, 29, 35, 41, 49, 55]

# Calculate the mean, median, and standard deviation of the list.
'''# Calculate mean, median, and standard deviation
mean = np.mean(numbers)
median = np.median(numbers)
std_dev = np.std(numbers)

# Display the results
print(f"Mean: {mean}")
print(f"Median: {median}")
print(f"Standard Deviation: {std_dev}")'''

# Plot the numbers
'''# Create a plot of the numbers
plt.plot(numbers, marker='o')
plt.title('Numbers Plot')
plt.xlabel('Index')
plt.ylabel('Value')
plt.grid(True)
plt.show()'''

# Then run all. 
# Then commit changes to git. 

# Worked on foster-eda
Followed the instructions on the EDA.md
Created a notebook titled foster-eda
Created a Markdown header with name, purpose and date
Created multiple python cells
    Import cell
    Iris data loaded
    Check dataset
    Statistics
    Histograms for numerical columns
    Display count and use loops to the value counts
    Feature Engineering
    Visualizations
    Run
    Add Markdowns with my observations