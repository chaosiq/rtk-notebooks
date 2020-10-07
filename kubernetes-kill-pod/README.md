# Mission for Killing a Kubernetes POD

Resources for running the mission to kill a Kubernets POD with the Chias
Toolkit, for full Mission details see
[Killing a POD Mission](impacting-kubernetes.ipynb).

## Running the Mission

You can run the mission in [Visual Studio Code](https://code.visualstudio.com/)
or with [Jupyter Notebooks](https://jupyter.readthedocs.io/en/latest/install.html#jupyter-notebook-interface) depending on your personal preference.

If you are not are already experienced Jupyter notedbooks then running with
Visual Studio would be the natural choice.

### Running a  Mission with Visual Studio Code

Download the notebook file and open it in
[Visual Studio Code](https://code.visualstudio.com/). If you dont have the
Python extension installed for Visual Studio code, Visual Studio will prompt
you to install the extension. Once the extension is installed Visual Studio
will prompt you to confirm that you trust the notebook file. If you select Trust
the Notebook file can be executed. You will need to ensure the Python environment
at the top right of the notebook is set to a suitable Python environment on your
machine. It is preferable that this is pointing to a [Python Virtual environment]
(https://docs.python.org/3/tutorial/venv.html). Once the Python environment is
selected you can execute the Python code sections in the notebook.


### Running with Jupyter Notebooks

You can run the notebook with
[jupyter notebook interface](https://jupyter.readthedocs.io/en/latest/install.html#jupyter-notebook-interface).

Installing the class Jupyter notebooks

```
pip install --upgrade pip
```

Install the Jupyeter Notebook:

```
pip install jupyter
```

Then download the Mission to your machine and the mission can be loaded and
run with: ```jupyter notebook impacting-kubernetes.ipynb```
