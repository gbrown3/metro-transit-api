# metro-transit-api

## How to set up your environment
1. Clone this repository
```
cd <yourDirectory>
git clone https://github.com/gbrown3/metro-transit-api
cd metro-transit-api
```
2. Make sure you have the latest version of Python and pip installed, then set up your virtual environment
```
python3 -m venv venv
. ./venv/bin/activate
```
You should now see `(venv)` before each line of your command line prompt.  

3. With your virtual environment activated, install flask
```
pip install flask
```

That's it! Remember to always activate your virtual environment with `. ./venv/bin/activate` in the `metro-transit-api` directory before you start the server.

## Running locally
1. In the `metro-transit-api` directory, with the virtual environment activated, simply run the following command
```
python server.py
```
You can shut down the server at any time by going back to the terminal window where you started it and entering `Ctrl + C`

## Project structure

### server.py
This is where the main Flask app lives.
