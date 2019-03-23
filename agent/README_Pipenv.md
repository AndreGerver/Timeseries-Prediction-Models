Using Pipenv with this Pipfile will get you the proper bayesian_optimization package as well as jupyter notebook kernel to work with it. Commands to get started:

**pipenv --python 3.7.2**

**pipenv shell**

**pipenv sync**

**python -m ipykernel install --user --name=my-virtualenv-name**


Replace "my-virtualenv-name" with the name of your pipenv environment. You can see it in the path of the command:

**which python**

Then you can:

**jupyter notebook --ip=127.0.0.1**