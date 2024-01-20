# Firebase functions server on Python

## Вeployment

1. You must have installed `Java` and `Node`

2. `npm install firebase`

3. `npm install -g firebase-tools`

## Firebase

0. `firebase login` (allow firebase ... info? - **y**)
1. `firebase init` (Are you ready to proceed? - **y**)
2. Select and **Enter**: 
 - `Emulators`
 - `Functions`


3. Select **Use an existing project** or **create** (you can create project on web site or in terminal)
4. Select `Python` and all - **y**
5. `cd functions` and `pip install -r requirements.txt`
6. `cd ..` - move in main
7. `firebase init hosting` - all **y** and **select project** (`git hub` - **no**)
8. `firebase init functions` - **y** (`dependencies now - ?` - **n**)

## If you have Error
`!!  functions: Failed to load function definition from source: Error: spawn "..." ENOENT`

The first way:
- `python -m pip install -r .\functions\requirements.txt -t .\functions\venv\Lib\site-packages\`

The second way:
- 1. cd functions/venv/Scripts
- 2. `python.exe -m pip install --upgrade pip`

## Hello world

**UnComments code in `main.py`**

`firebase emulators:start`

your project name in `firebaserc`

localhost:5001/<Your project name (id)>/us-central1/on_request_example