
## Introduction

What is an API?

An Application Programming Interface (API) allows pieces of code to interact with one another. Developers use APIs to build their websites with specific features, like a Google Maps interface, instead of having to write code from scratch. Some may be open-source, while others charge a fee for implementation. You typically need to register a developer account or have some other means of authentication for APIs.

An API typically has three core elements:

Access: Who is the user accessing the service?
Request: What is the service or data being requested? This includes both methods (what questions do you need answered with the data or service solicited?) and parameters (supplementary details).
Response: How does the system respond to the request?



## Installations

Importing libraries

Python

Jupyter notebook (label: good first issue)

Jupyter interactive notebook

Pandas (label: good first issue) Flexible and powerful data analysis / manipulation library for Python, providing labeled data structures similar to R data. Frame objects, statistical functions, and much more.

numpy (label: good first issue)

pip install numpy
It is the core library for scientific computing, which contains a powerful n-dimensional array object.

requests

PrettyTable

json




## Running the project

Create pretty table object

tableobj = PrettyTable()

Store API Key in a variable & concatenate it with API endpoint

KeyVal = '37d0d5d1-eca3-4739-8723-8b4dce81be2b'

api_endpoint = 'https://pro-api.coinmarketcap.com/v1/cryptocurrency/listings/latest?CMC_PRO_API_KEY='
api_endpoint += KeyVal
api_endpoint

Fetch data in JSON format

Store data in Pretty Table

Create External Field names and assign as column names in Pretty table


## Conclusion


 
In this process we can fetch data from coinmarketcap