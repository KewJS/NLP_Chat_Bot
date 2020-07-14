# NLP_Chat_Bot
Create first Chat Bot from Text using NLP technology

# Chat Bot
Sheet1.csv contains 80 user responses, in the responsetext column, to a therapy chatbot. Bot said: 'Describe a time when you have acted as a resource for someone else'.  User responded. If a response is 'not flagged', the user can continue talking to the bot. If it is 'flagged', the user is referred to help.

Sheet2.csv contains 125 resumes, in the resumetext column. Resumes were queried from Indeed.com with keyword 'data scientist', location 'Vermont'. If a resume is 'not flagged', the applicant can submit a modified resume version at a later date. If it is 'flagged', the applicant is invited to interview.

[Deep NLP](https://www.kaggle.com/samdeeplearning/deepnlp)

## Structuring a repository
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

## Resources
[Medium: Web Traffic Time Series Prediction Using ARIMA & LSTM](https://medium.com/@jyshao53/web-traffic-time-series-prediction-using-arima-lstm-7ef3911845ae)

[towardatascience: Web Traffic Forecasting](https://towardsdatascience.com/web-traffic-forecasting-f6152ca240cb)
