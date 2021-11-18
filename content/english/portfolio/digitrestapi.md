---
title: "RESTAPI digit predictor"
date: 2020-12-1T12:14:34+06:00
image: "images/portfolio/item5.png"
categories: ["Web", "Machine Learning"]
description: "RESTAPI to predict digit"
draft: false
project_info:
- name: "Project Link"
  icon: "fas fa-link"
  content: "https://keras-flask.herokuapp.com/predict "
---

REST API to recognise hand written digits built with keras & flask hosted on heroku.

## Usage

Make a post request to **https://keras-flask.herokuapp.com/predict** sending an image of the number you wish to predict. 

### Example using python.

```python
import requests 

resp = requests.post("https://keras-flask.herokuapp.com/predict", files={'file': open('eight.png', 'rb')})

print(resp.text)
```

## Resource

[Tutorial by Python Engineer](https://youtu.be/bA7-DEtYCNM)
