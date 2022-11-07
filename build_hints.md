
Use jsonschema2rst to pull documentation from the schema file into rst.

```
pip install jsonschema2rst
```

See section in conf.py that uses this to transform schema to rst.


## Install sphinx

```
conda create -n sphinx python=3.9
conda activate sphinx
conda install sphinx
conda install -c conda-forge sphinxcontrib-contentui
conda install sphinx_rtd_theme sphinx-toolbox
```
