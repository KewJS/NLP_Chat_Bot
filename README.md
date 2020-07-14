# NLP_Chat_Bot
Create first Chat Bot from Text using NLP technology

# Chat Bot
Sheet1.csv contains 80 user responses, in the responsetext column, to a therapy chatbot. Bot said: 'Describe a time when you have acted as a resource for someone else'.  User responded. If a response is 'not flagged', the user can continue talking to the bot. If it is 'flagged', the user is referred to help.

Sheet2.csv contains 125 resumes, in the resumetext column. Resumes were queried from Indeed.com with keyword 'data scientist', location 'Vermont'. If a resume is 'not flagged', the applicant can submit a modified resume version at a later date. If it is 'flagged', the applicant is invited to interview.

[Deep NLP](https://www.kaggle.com/samdeeplearning/deepnlp)

# getting started

To get started, first identify whether you:

- Would like to run the tutorial material on servers hosted elsewhere, to avoid installation,
- Prefer to use the `conda` package manager (which ships with the Anaconda distribution of Python),
- Prefer to use `pipenv`, which is a package authored by Kenneth Reitz for package management with `pip` and `virtualenv`, or
- Only want to view the website version of the notebooks.

## 1. Clone the repository locally

In your terminal, use `git` to clone the repository locally.

```bash
git clone https://github.com/KewJS/NLP_Chat_Bot.git
```

Alternatively, you can download the zip file of the repository at the top of the main page of the repository. 
If you prefer not to use git or don't have experience with it, this a good option.

## 2. Set up your environment

### 2a. `conda` users

If this is the first time you're setting up your compute environment, 
use the `conda` package manager 
to **install all the necessary packages** 
from the provided `environment.yml` file.

```bash
conda env create -f environment.yml
```

To **activate the environment**, use the `conda activate` command.

```bash
conda activate nlp_chatbot
```

**If you get an error activating the environment**, use the older `source activate` command.

```bash
source activate nlp_chatbot
```

To **update the environment** based on the `environment.yml` specification file, use the `conda update` command.

```bash
conda env update -f environment.yml
```

### 2b. `pip` users

Please install all of the packages listed in the `requirement.txt` file manually. 
An example command would be:

```bash
pip install -r requirement.txt ...
```

### 3. Open your Jupyter notebook

1. You will have to install a new IPython kernelspec if you created a new conda environment with `environment.yml`.

    python -m ipykernel install --user --name nlp_chatbot --display-name "Python (nlp_chatbot)"

You can change the `--display-name` to anything you want, though if you leave it out, the kernel's display name will default to the value passed to the `--name` flag.

2. In the terminal, execute `jupyter notebook`.

Navigate to the notebooks directory...

# Structuring a repository

An integral part of having reusable code is having a sensible repository structure. That is, which files do we have and how do we organise them.
- Folder layout:
```bash
project_name
├── docs
│   ├── make.bat
│   ├── Makefile
│   └── source
│       ├── conf.py
│       └── index.rst
├── src
│   └── analysis
│       └── __init__.py
|   └── train
│       └── __init__.py
|   └── Config.py
|   └── cmd.py
|   └── testing_tasks.py
├── .gitignore
├── README.md
├── requirements.txt
├── environment.yml
└── setup.py
```

# Acknowledgements

Development of this type of material is almost always a result of years of discussions between members of a community. 
We'd like to thank the community and to mention several people who have played pivotal roles in our understanding the the material: 
Teo Kai Wen

# Further Reading & Resources

Further reading resources that are not specifically tied to any notebooks.

- [Building a Simple Chatbot from Scratch in Python (using NLTK)](https://github.com/parulnith/Building-a-Simple-Chatbot-in-Python-using-NLTK)
- [Advanced NLP Projects with TensorFlow 2.0](https://github.com/PacktPublishing/Advanced-NLP-Projects-with-TensorFlow-2.0)
- [Simple-Python-Chatbot](https://github.com/jerrytigerxu/Simple-Python-Chatbot)
