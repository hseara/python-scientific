# python

This course is based in a jupyer notebook. We will use its newest flavour named [jupyterlab](https://jupyterlab.readthedocs.io/en/stable/).

# Prerequisites for the course:

- Bring your own laptop. The course should work with any laptop with either linux, MacOSX or Windows.
- [anaconda](https://www.anaconda.com/products/individual#Downloads)
- Course environment
  - Install an enviroment for the course:
    ```
    conda create --name py38-course python=3.8 jupyterlab numpy nodejs matplotlib scipy pandas
    ```
  - Activate the environment
    ```
    conda activate py38-course
    ```
  - Configure jupyter lab
   - [Table of contents](https://github.com/jupyterlab/jupyterlab-toc)
     ```
     jupyter labextension install @jupyterlab/toc
     ```
   - [Variable inspector](https://github.com/lckr/jupyterlab-variableInspector)
     ``` 
     jupyter labextension install @lckr/jupyterlab_variableinspector
     ```
   - [pycodestyle_magic and pep8](https://github.com/mattijn/pycodestyle_magic)
     ```
     conda install flake8 pycodestyle
     pip install pycodestyle_magic
     ```
  - Deactivate the active environment
    ```
    conda deactivate
    ```