# Network Tools and Scapy Notebooks

Jupyter Notebooks for learning bash network utility tools and scapy library - a powerful interactive packet manipulation program for Python

Scapy: https://github.com/secdev/scapy/

## Scapy documentation: https://scapy.readthedocs.io/en/latest/


# Requirements

- Linux Bash
- gcc
- Jupyter Notebook
- Jupyter Lab
- Python3

# Install Required Tools

-   Install Python 3.x Miniconda for Linux: https://conda.io/en/latest/miniconda.html
-   Once miniconda is installed, install Jupyter Notebook using conda
    -   `conda install notebook`
-   install minimal C kernel using terminal
    -   `sudo pip install jupyter-c-kernel`
    -   `sudo install_c_kernel`
    - NOTE: if conda is used to install notebook, you must run notebook as root to run C kernel

# Play with Notebooks

-   Clone/download this repository
-   You must run the notebook as root to use some scappy features such as sniff()
-   Using a terminal cd into the repo folder and run 
    ```# jupyter notebook --allow-root`
-   Open Introduction.ipynb chapter and access all the notebooks
