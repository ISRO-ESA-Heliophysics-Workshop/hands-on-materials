# How to run the SPICE tutorial

From within a new environment:
```sh
python -m venv venv
. venv/bin/activate
python -m pip install -r requirements.txt
```
This will also install the `jupyter` package. Then, still within the environment, install it for Jupyter with
```
ipython kernel install --user --name=spice-demo-isro
```
and run
```
jupyter notebook
```
or
```
jupyter-lab
```
then open this notebook and run it with the kernel `spice-demo-isro`.
