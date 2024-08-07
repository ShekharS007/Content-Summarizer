# Install virtualenv using pip3
pip3 install virtualenv

# Create a virtual environment named my_env
virtualenv my_env

# Activate the virtual environment my_env
source my_env/bin/activate

# Install required libraries in my_env
pip install transformers==4.35.2 torch==2.1.1 gradio==4.17.0 langchain==0.0.343 ibm_watson_machine_learning==1.0.335 huggingface-hub==0.19.4

# Install ffmpeg, a multimedia framework
sudo apt install ffmpeg -y

# Update the package lists for upgrades and new package installations
sudo apt update

