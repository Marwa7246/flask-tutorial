# flask-tutorial
### check python version 
python3 --version
### Check pip3 version
pip3 --version
### install venv globally
sudo apt install -y python3-venv
### Create enviroments in the project folder
python3 -m venv env
### Check content of env folder
ls env ==> bin  include  lib  lib64  pyvenv.cfg
### Activate enviroments
source env/bin/activate ==> prompt will be : 
(env) marwa@pop-os:~/learning-python/flask-tutorial$
### Install flask 
pip install flask
### check flask version 
python -c "import flask; print(flask.__version__)"
### Run the app 
export FLASK_APP=app  
export FLASK_ENV=development  
flask run