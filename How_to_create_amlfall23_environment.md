## Downloading and installing Python using Anaconda
`https://www.anaconda.com/products/distribution`

## Creating a vitual python environment for AML Fall 2023

### Important to use the python engine 3.10 
### Open an Anaconda prompt (as administrator) and type:
`conda create -n amlfall23 python=3.10`

`conda activate amlfall23`

### If GPU is available for tensorflow
`conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0`

### tensorflow for CPU and GPU. Windows do not support tensorflow>2.10
`python -m pip install "tensorflow<2.11"`

### Jupyter notebook will be usefull
`conda install -c anaconda jupyter`

### Other libraries we will be using throughout the course
`conda install numpy pandas scikit-learn matplotlib`

### Verifying Tensorflow GPU installation:
`python -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"`
> [PhysicalDevice(name='/physical_device:GPU:0', device_type='GPU')]


### Alternative install using amlfall23.yml
`conda env create -f amlfall23.yml`


### Using Google colab (free account)
- [Google Colab](https://colab.research.google.com)


### There are many great IDE's for python:
- [PyCharm](https://www.jetbrains.com/pycharm/)
- [Spyder](https://www.spyder-ide.org)
- [Visual Studio Code](https://code.visualstudio.com)
- [Jupyter Notebook](https://jupyter.org)
- [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/)

