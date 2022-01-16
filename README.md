# Installation:

## Create a virtual env:

```
python3 -m venv venv
```

## Enter the virtual env:

```
source venv/bin/activate
```

## install dependencies:

```
pip install -r requirements.txt
```

# Setup:

You'll need to generate Oauth2 Credentials json file, and put it in the root directory, it should be named "credentials.json"

## Execute the script

```
python fetch.py
```

This will open in the browser to authenticate to you gmail account, and generates a "token.json" file in you root directory.