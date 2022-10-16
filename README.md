# emoji-food
emoji food front end 


## Using venv to isolate dependencies
1. Use the venv command to create a virtual copy of the entire Python installation. This tutorial creates a virtual copy in a folder named env, but you can specify any name for the folder.

cd your-project
python -m venv env
Using venv to isolate dependencies

2. Set your shell to use the venv paths for Python by activating the virtual environment: 
source env/bin/activate

3. Now you can install packages without affecting other projects or your global Python installation:
pip install google-cloud-storage

4. Installing the Cloud Client Libraries for Python
pip install --upgrade google-cloud-storage

## 2. Install packages for Python
2.1. source env/bin/activate

2.2. To install Flask, run the following command:
pip install flask

2.3 Once the installation is complete, run the following command to confirm the installation:
python -c "import flask; print(flask.__version__)"




export FLASK_APP=hello

export FLASK_ENV=development

flask run

## Naming 

https://www.conventionalcommits.org/en/v1.0.0/ 
