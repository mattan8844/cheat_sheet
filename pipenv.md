# Pipenv Cheat Sheet

## Install pipenv
```
pip3 install pipenv
```
## Activate
```
pipenv shell
```
## Check version of Python
```
python --version
```
## Check path
```
python
>>> import sys
>>> sys.executable
quit()
```
## Install a package
```
pipenv install camelcase
```
## Check local packages
```
pipenv lock -r
```
## Uninstall a package
```
pipenv uninstall camelcase
```
## Install a dev package
```
pipenv install nose --dev
```
## Install from requirements.txt
```
pipenv install -r ./requirements.txt
```
## Check security vulnerabilities
```
pipenv check
```
## Check dependency graph
```
pipenv graph
```
## Ignore pipfile
```
pipenv install --ignore-pipfile
```
## Set lockfile - before deployment
```
pipenv lock
```
## Exiting the virtualenv
```
exit
```
## Run with pipenv
```
pipenv run *
```

# Homepage
https://github.com/pypa/pipenv

# Usage

## Initialize
```
$ export PIPENV_VENV_IN_PROJECT=true
$ pipenv --python /usr/bin/python3 install --skip-lock
$ pipenv shell
```
* To initialize a Python 3 virtual environment: `$ pipenv --three`
* To initialize a Python 2 virtual environment: `$ pipenv --two`

## Locate
```
# Locate the project
$ pipenv --where
     /Users/user/code/test

# Locate the virtualenv
$ pipenv --venv
     /Users/user/.local/share/virtualenvs/test-Skyy4vre

# Locate the Python interpreter:
$ pipenv --py
    /Users/user/.local/share/virtualenvs/test-Skyy4vre/bin/python
```

## Other commands
```
$ pipenv install flask==0.12.1

$ pipenv graph
```