# py_test_01

## Add a Python Virtual Environment

Create a virtual environment:
```
python3 -m venv .venv
```

Activate the virtual environment:
```
source my_venv/bin/activate
```

Or make the virtual environment hidden:
```
python3 -m venv .venv
source .venv/bin/activate
```

Install packages in the virtual environment:
```
python3 -m pip install <package-name>
python3 -m pip install --upgrade pip
python3 -m pip install pandas
python3 -m pip install numpy
python3 -m pip install matplotlib
python3 -m pip install sklearn
```

N.B These packages can take up quote a bit of space - 100s MB to GB so only install those you actually need!

Deactivate the virtual environment:
```
deactivate
```

## Create a Repo on GitHub

Push a repo up to git hub using:
```
git init
git add .
git commit -m "My personal project."
git remote add origin git@github.com:DarkMe67/py_test_00
```
Create an empty project of the same name on git hub then push the files.
```
git push -u origin master
```
