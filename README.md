# Research Assistant powered by Groq

This application is a research tool designed to leverage the capabilities of Groq's hardware accelerated computing and Tavily API. Follow the steps below to set up and run the application on your local machine.

## Setup Instructions

### 1. Fork and Clone the Repository

First, fork the repository to your GitHub account by clicking on the "Fork" button at the top right of this page. Then, clone the forked repository to your local machine:

```shell
git clone https://github.com/fwromano/perplexed.git
cd perplexed


### 2. Create a virtual environment

```shell
python3 -m venv ~/.venvs/aienv
source ~/.venvs/aienv/bin/activate
```

### 3. Export your Groq & Tavily API Key

```shell
export GROQ_API_KEY=***
export TAVILY_API_KEY=***
```

### 4. Install libraries

```shell
pip install -r requirements.txt
```

### 5. Run Streamlit App

```shell
streamlit run app.py
```

- Open [localhost:8501](http://localhost:8501) to view your Groq Researcher.
