How to install Theano, TensorFlow and Keras
- For Mac users:
    + Open your main terminal or the Anaconda Prompt and enter the following commands:
    1. pip install theano
    2. pip install tensorflow
    3. pip install keras
    4. conda update --all
- For Windows and Linux users:
    + In Spyder, go to Tools and Open Anaconda Prompt. Then enter the following commands:
    1. Create a new environment with Anaconda and Python 3.5:
        conda create -n tensorflow python=3.5 anaconda
    2. Activate the environment:
        activate tensorflow
    3. After this you can install Theano, TensorFlow and Keras:
        conda install theano
        conda install mingw libpython
        pip install tensorflow
        pip install keras
    4. Update the packages:
        conda update --all
    5. Run Spyder:
        spyder
    + To install TensorFlow on your GPU (optional):
    1. pip install tensorflow-gpu
