# crobThesisSetupUbuntu1204
This is a description (for myself) on how to seet up Ubuntu 12.04 with Caffe neural network framework &amp; python3.5 + packages for my thesis experiments.

1. First thing is to follow this guide here (https://github.com/BVLC/caffe/wiki/Install-Caffe-on-EC2-from-scratch-%28Ubuntu,-CUDA-7,-cuDNN%29) on how to install Caffe on Ubuntu 12.04
2. Next set up any IDE you wish to use, pycharm in my case
3. Next install python3.5 (http://askubuntu.com/questions/682869/install-python-3-5-on-vivid-using-apt-get)
4.    sudo add-apt-repository ppa:fkrull/deadsnakes
      sudo apt-get update
      sudo apt-get install python3.5

5. Once all that is taken care of, install packages needed for thesis work:
6.  Numpy
7.  Scipy
8.  matplotlib
8.  sci-kit learn
9.  sci-kit image
9.  h5py
9.  pillow
10.  tiffile.py (only needed for reading in raw data files)

11.   Install packages via:  (http://stackoverflow.com/questions/18785063/install-numpy-in-python-virtualenv)
12.   ex: virtualenv ~/.venvdir/venv/ && ~/.venvdir/venv/bin/pip3.5 install foo
