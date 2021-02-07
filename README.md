# Twitter Sentiment-Dashboard

## DUBHACKS 2020 Project
### Zane Priebe, Assaf Vayner, Zedong(Tom) Wu

A web-app displaying tweets, set in a UI that exposes user to more content syncronously which encourages seeing multiple viewpoints regarding the content available per search query. This web app also subtly assists the user in reading impartial tweets which have a sentiment score near 0. This means that the phrasing of the tweet does not seek to persuade using exciting language.

Hosted at: [https://twitter-sentiment-dashboard-1.herokuapp.com/](https://twitter-sentiment-dashboard-1.herokuapp.com/)

### Dependencies:
- pandas
- Plotly-Dash web framework for python
- Twitter API, specifically the python-twitter interface (API keys and tokens not provided)

#### Virtual Environment Setup
- Start a virtual environment inside directory where this README is found
- use command `python -m venv venv`
- activate the virtual environment
    - `source venv/bin/activate` in linux
    - In windows `venv\Scripts\Activate.ps1` on powershell, and `venv\Scripts\activate.bat` on cmd

- run command `pip install -r requirements.txt`
