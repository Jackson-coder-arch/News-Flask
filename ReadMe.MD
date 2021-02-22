# Project Name
News Api
# Project Description
This is a news app that enables you to get an api_key that helps you get news resources from the server
# Author(s) Information
Jackson Ikonya

# BDD
* Build the basic website that displays the various news source.
* Have a view article from selected news sources.
* User must see the images,description,time.

## Setup Instruction
* Clone the repo:
    git clone https://github.com/rose-okoth/News-API​
* Switch into the directory:
    cd News-API

## Running the application

* Create the virtual environment

    $ python3 -m venv --without-pip virtual
    $ source virtual/bin/env
    $ curl https://bootstrap.pypa.io/get-pip.py | python

* Installing Flask and other Modules

    $ python3 -m pip install Flask
    $ python3 -m pip install Flask-Bootstrap
    $ python3 -m pip install flask-script

* Setting up the API Key

    To be able to gather article info from the News API you will need an API Key.

    Visit https://newsapi.org/ and register for an API key.

    In the root directory of the project folder create a file: start.sh

    Insert the following info into it:

    export NEWS_API_KEY='<Your-Api-Key>'
    python3.6 manage.py server
    Insert the API Key you received from News Api where <Your-Api-Key> is.
* To run the application, in your terminal:

    $ python3.9 manage.py


## Testing the App
* To run the tests for the class files:
    $  python3 manage.py tests



# Technologies Used
* Python
* Flask
* HTML
* Bootstrap

# Live Link
Link to News Trends: https://matokeo-hivi-sasa.herokuapp.com/


# Contact Information
* Email: newstrends@gmail.com

# License and Copyright Information
Copyright(c) 2021 - Jackson-coder-arch.
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
Reference: [MIT License](https://opensource.org/licenses/MIT)