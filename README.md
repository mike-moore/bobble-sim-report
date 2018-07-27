# Bobble-Bot Sim Development Notebook
This repository holds the Jupyter notebook that was created during
the development of the Bobble-Bot simulation. 


## How to edit the notebooks

### Clone this repo
```shell
git clone https://github.com/mike-moore/bobble-sim-report.git
```

### Install Jupyter Notebook
```shell
sudo apt-get -y install ipython ipython-notebook
pip install jupyter
```

### Install the theme (optional)
```shell
cd ~/.jupyter/custom/
git clone https://github.com/neilpanchal/spinzero-jupyter-theme.git .
```

### Install the extensions (optional)
```shell
pip install --user jupyter_contrib_nbextensions
jupyter contrib nbextension install --user
```
Now go into the extensions configuration page and enable Table of Contents 2 and Code Folding

http://localhost:8890/tree#nbextensions_configurator

### Run the jupyter-notebook server
```shell
jupyter-notebook
```

