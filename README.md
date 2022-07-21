# python_example
A simple example of a Python project setup in git. Before executing the steps below you need to have git installed 
and the appropriate version of python installed that you want to use. Note that it may seem confusing that you need
python installed in order to create a python virtual environment. 

When you install python be default there will be a lib dir and under this you will find site packages folder which
is the location that pip will install libraries. In order to prevent all libraries being installed here you create a 
python virtual environment which has a full copy of python and its own site packages. This ensures that pip install
command installs libraries in this environment and NOT your system install of Python. This also allows you to easily 
test out new version of python and libraries by having different python environments.

### Setup
* git clone https://github.com/dmcharg/python_example.git
* cd python_example
* python3 --version 
* python3 -m venv myenv
* source myenv/bin/activate
* pip install --upgrade pip
* pip install -r ./requirements.txt
* Open pycharm and open root folder i.e python_example
* run hello.py or numpy_example.py






