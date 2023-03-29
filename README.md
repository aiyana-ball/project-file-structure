# Calculator

## Overview

Basic calculator with:
- Addition
- Subtraciton
- Multiplication
- Division

## One-Time Project Setup

Follow these directions once:

1. In GitHub, click on the "Fork" button and fork the repository to your GitHub account. This will make a copy of the project in your GitHub account.
   
2. Navigate to desired folder in terminal.
   
3. "Clone" (download a copy of this project) into your folder. This command makes a new folder called `calculator`, and then puts the project into this new folder.

```bash
$ git clone ...
```
Use `ls` to confirm there's a new project folder

4. Move your location into this project folder

```bash
$ cd calculator
```

5. Create a virtual environment named `venv` for this project:

```bash
$ python3 -m venv venv
```

6. Activate this environment:

```bash
$ source venv/bin/activate
```

Verify that you're in a python3 virtual environment by running:

- `$ python --version` should output a Python 3 version
- `$ pip --version` should output that it is working with Python 3

7. Install dependencies once at the beginning of this project with

```bash
# Must be in activated virtual environment
$ pip install -r requirements.txt
```
## How to run tests

To check if the tests are running as expected, run the following command:

```bash
python3 -m pytest test_X.py
```

Replace X with addition, subtraction, multiplication, or division. If the file you are testing is nested in a sub-directory, please remember to cd into the directory before running the command.



