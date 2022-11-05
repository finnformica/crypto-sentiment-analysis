# Crypto Sentiment Analysis

## Introduction

Juypter Notebook to play around with pre-trained sentiment analysis models using HuggingFace and transformers pipelines. Next I would like to train my own model which would require finding labelled data somewhere...

## Dependencies

- Python 3.10+
- pip 22.2.2+

## Getting Started

1. Clone the respository

```
git clone
```

2. Setup Twitter API credentials by following this [guide](https://developer.twitter.com/en/docs/tutorials/step-by-step-guide-to-making-your-first-request-to-the-twitter-api-v2)

3. Create a new python file called "twitterKeys.py" and paste the API keys into a dict

```python
keys = {
    "apiKey": "xxxx-xxxx",
    "secretKey": "xxxx-xxxx",
    "bearerToken": "xxxx-xxxx"
}
```

4. Run the Jupyter Notebook!
