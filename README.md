
# What's inside the box? An introduction to explainability in finance
### Presentation: [Explainability in finance](workshop/PyLadies_Explainable_AI.pdf)

## Workshop description
Building a machine learning model is just one piece of the puzzle in data science; explaining how it works is just as important, especially in finance where transparency and explainability are key.

During this workshop, we'll show you how to look inside your model and understand what’s going on. We'll explore techniques to make your models easier to explain and discuss their opportunities and downfalls.

## File Structure
```
.   
├── solutions/ 					# Solutions directory   
│   ├── Explainability_solutions.ipynb		# Notebook with solutions to workshop  
│   └── Explainability_solutions_extended.ipynb	# Notebook with additional exercises and their solutions to explore by yourself
│  
├── workshop/					# Workshop directory  
│   ├── Explainability.ipynb			# Notebook with exercises  
│   ├── mortgage_churn.csv			# Data for workshop  
│   └── PyLadies_Explainable_AI.pdf		# Presentation
│   
├── README.md 									
└── requirements.txt				# List of dependencies  
```

## Requirements
- Python 3.10 or higher
- Jupyter notebook

## Usage
### Jupyter option
* Clone the repository with `git clone https://github.com/pyladiesams/intro-to-explainabilty-in-finance-oct2024`
* Setting up your environment 
Install environment: `python -m venv explainability_venv`      
Activate environment: `explainability_venv\Scripts\activate` or `source explainability_venv/bin/activate` depending on OS   
Install dependencies: `pip install -r requirements.txt`  
Install notebook kernel for the venv: `python -m ipykernel install --user --name explainability_venv`   
Start notebook with `jupyter notebook` and select kernel with environment


### Google colab option
* Open [Collab notebook](https://colab.research.google.com/drive/1oP5O6ksQ64ulCjtkqdzoHtu8uxgigVR5?usp=sharing)
* Create a copy of this notebook in your Google Drive. Go to Menu options: File > Save a copy in Drive. This will open a copy of the notebook in a new window.

## Video record
Re-watch [this YouTube stream](https://youtube.com/live/SrrH_eLx5_s)

## Credits
This workshop was set up by @pyladiesams, [Magdalena Zych](https://www.linkedin.com/in/ma-zych/), [Petra Gibcus](https://www.linkedin.com/in/petra-gibcus-0b94a547/), [Amirsalar Molaei](https://www.linkedin.com/in/amirsalarmolaie/), [Dana Tokmurzina](https://www.linkedin.com/in/dana-tokmurzina-107378126/), [Ellie Nasiri](https://www.linkedin.com/in/elahe-nasiri/), [Dana van der Wende](https://www.linkedin.com/in/dana-van-der-wende-266b182b/), [Nihed Harrak](https://www.linkedin.com/in/nihedharrak/).
