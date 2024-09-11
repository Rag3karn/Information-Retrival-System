# Information Retrieval from Multiple pdf 😁😁 using PalM2

# How to run?

### Steps

Clone the Repository

'''bash
Project Repo:
'''

### Step 01: Create a conda environment after opening the repository

'''bash
conda create -n llmapp python=3.12 -y
'''

'''bash
conda create llmapp

### STEP 02: Install the requirements

'''bash
pip install -r requirements.txt
'''

### STEP 03: Create a '.env' file in the root directory and add your GOOGLE_API_KEY as follows

'''ini
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
'''

'''bash

# Finally run the follwing command
'''
streamlit run app.py
'''

Now,
'''bash
open up : <http://localhost:8501>
'''

### Techstack used

-Python
-Langchain
-Streamlit
-PalM2
-FAISS
