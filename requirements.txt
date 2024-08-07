### Install virtualenv
pip3 install virtualenv

### Create a virtual environment
virtualenv my_env

### Activate the virtual environment
source my_env/bin/activate

### Install required libraries in my_env
pip install transformers==4.35.2 
torch==2.1.1 
gradio==4.17.0 
langchain==0.0.343 
ibm_watson_machine_learning==1.0.335 
huggingface-hub==0.19.4

### Update the package lists for upgrades 
sudo apt update

### Install ffmpeg, a multimedia framework
sudo apt install ffmpeg -y

