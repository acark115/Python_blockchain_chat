Instructions to run
Clone the project,

$ git clone https://github.com/keremarda115/Python_blockchain_chat.git
Install the dependencies,

$ cd Python_blockchain_chat
$ pip install -r requirements.txt
Start a blockchain node server,

# Windows users can follow this: https://flask.palletsprojects.com/en/1.1.x/cli/#application-discovery
$ export FLASK_APP=node_server.py
$ flask run --port 8000
One instance of our blockchain node is now up and running at port 8000.

Run the application on a different terminal session,

$ python run_app.py
The application should be up and running at http://localhost:5000.

Here are a few screenshots