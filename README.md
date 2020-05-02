# API-using-python-for-diabetes
I am going to build a simple python API using flask for diabetes prediction machine learning model using Gaussian Naive Bayes Model by SKLearn
API(Application Programming Interface)

Many Internet companies, such as Facebook, Google, and Twitter provides Application Programming Interfaces (or API's) that you can use to build your own applications.

It is a collection of communication protocols and subroutines used by various programs to communicate between them. A programmer can make use of various API tools to make its program easier and simpler.

API helps two programs or applications to communicate with each other by providing them with necessary tools and functions. It takes the request from the user and sends it to the service provider and then again sends the result generated from the service provider to the
desired user.

An API is a set of programming instructions and standards for accessing web based software applications. A wrapper is an API client, that are commonly used to wrap the API into easy to use functions by doing API calls itself                                             FLASK:
Flask maps HTTP requests to Python functions. In this case we have mapped one URL path (‘/’) to one function. Flask checks if there is a match between the path provided and a defined function.

Flask runs the code in the function and displays the returned result in the browser.The process of mapping URLs to functions is called
Routing.

API(Application Programming Interface)

API methods:

1. get

2. post

3. put

4. delete


API(Application Programming Interface)

from flask import Flask

app = Flask(__name__) #Creates the Flask application object, which
contains data about the application and also methods (object functions) that tell the
application to do certain actions

@app.route('/')

def index():

return 'Hello World'

if __name__ == '__main__':

app.run(debug=True) #Starts the debugger

Output:

Hello World
