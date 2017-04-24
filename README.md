# BlindBites2.0

How To Start

Step 1 - Clone Repo
$ git clone https://github.com/27amogh/BlindBites2.0.git
$ cd BlindBites2.0

Step 2 - Initialize and activate a virtualenv
$ virtualenv -p python2.x --no-site-packages env
-include your own python version in the "python2.x"
$source env/bin/activate

-For windows (follow same python procedure as for mac)
$ virtualenv --python=C:\Python2X\python.exe --no-site-packages env
$ env\Scripts\activate

Step 3 - Install the dependencies
$ pip install -r requirements.txt

Step 4 - Run the development server
$ python app.py

Step 5
Navigate to "http://localhost:5000"
-the above localhost is wrong. Tbe new localhost will appear in the terminal after following this procedure
-The Infrasctructure for the Yelp Api as well as the remaining features will be appended back to Githuh soon. I am currently trying to pull the Yelp Api into a new sudo database so that I can set my own parameters for search or have an AI sort through its own criteria versus only being able to follow the Yelp parameters.
