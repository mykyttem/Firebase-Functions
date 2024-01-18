# Firebase functions server on Python

## Вeployment

1. You must have installed `Java` and `Node`

2. `npm install firebase`

3. `npm install -g firebase-tools`


## Firebase

0. `firebase login`
0.1 `allow firebase ... info?` - y
1. `firebase init hosting` 
2. `firebase init`
3. `Are you ready to proceed?` - y
4. Select Emulators and Functions
5. Select project or create
6. Select `Python`
7. `OverWrite?` - y
8. `Do you want to install dependecies now?` - y
9. All overwrite
10. `pip install firebase-admin`
11. cd functions/venv/Scripts
12. `python.exe -m pip install --upgrade pip`
13. `cd ..` and `cd ..` for move in main `function` catalog
14. `python -m pip install -r .\requirements.txt -t .\venv\Lib\site-packages\`
15. `cd ..`
16. `firebase init emulators`
17. `firebase deploy`

## Hello world

UnComments in `main.py``

`firebase emulators:start`

your project name in `firebaserc`

localhost:5001/<<Your project name (id)>>/us-central1/on_request_example