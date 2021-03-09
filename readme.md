# COD API HOW TO

COD API Docs built by the community: https://documenter.getpostman.com/view/5519582/SzzgAefq
## Run it with jupyter installed globally

````shell
pip install -r requirements.txt
````

````bash
jupyter notebook .
````

## Run it with jupyter in a virtualenv

If you don't want to install jupyter globally and/or want to play around with different versions of python modules you can either run in a virtual python environment or with docker.
This gives you more flexibility to try and test different versions for different projects.

For this I use pyenv.
https://realpython.com/intro-to-pyenv/
https://github.com/pyenv/pyenv

Create a new virtual environment specifically for this project, choose a python version and give it a name. For example I'll be using python 3.8.2 with the name "cod_api".

````bash
pyenv virtualenv 3.8.2 cod_api
````

````bash
pyenv local cod_api
````

## Run locally with docker