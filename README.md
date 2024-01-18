# Firebase functions server on Python

## Вeployment

1. You must have installed `Java` and `Node`

2. `npm install firebase`

3. `npm install -g firebase-tools`


## Firebase

0. `firebase login` 
1. cd functions/Scripts/venv
2. `python.exe -m pip install --upgrade pip`
3. `cd ..` and again `cd ..` for move in main catalog
4. `firebase init`
5. Select Emulators and Functions
6. Select project or create
7. Others `Yes`
8. All overwrite

## Hello world

`firebase emulators:start`

http://127.0.0.1:5001/<<Your project name (id)>>/us-central1/on_request_example