=========
AI Models
=========

:Version: 1.0.0
:Status: final
:Author: José Antonio Perdiguero López, Miguel Barrientos Fernández

Artificial Intelligence models.

Install
=======
Install system requirements (On Ubuntu)::

    sudo apt-get install -y build-essential libblas-dev liblapack-dev libatlas-dev libatlas-base-dev python3-dev gfortran postgresql-server-dev-9.3 python3-pip
    sudo apt-get build-dep -y python3-matplotlib
    sudo apt-get install -y libzmq-dev

Make a virtualenv::

    pip3 install virtualenv virtualenvwrapper
    echo "source /usr/local/bin/virtualenvwrapper.sh" >> ~/.bashrc
    echo "export WORKON_HOME=$HOME/.virtualenvs" >> ~/.bashrc
    mkvirtualenv scienv --python=/usr/bin/python3
    cd /path/to/project
    add2virtualenv .

Install SciPy stack dependencies::

    sudo apt-get install gfortran libopenblas-dev liblapack-dev

Install TensorFlow: `TensorFlow <https://www.tensorflow.org>`_

Install python requirements::

    pip install -r requirements.txt
