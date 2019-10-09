# oreilly-ml

Set up dev environment:
1. Install Python 3: www.python.org
2. Create virtual environment in your working directory to keep your Python work tidy:
   1. `$ python -m venv myenv`
   2. `$ myenv\Scricts\activate` -or- `$ source myenv/bin/activate`
3. Install ML tools:
    `$ pip install scikit-learn numpy scipy pandas matplotlib jupyter`

Set up Jupyter environment:
1. `pip install jupyter_contrib_nbextensions`
2. `jupyter contrib nbextension install`
3. `jupyter nbextensions_configurator enable`
4. `pip install jupyterthemes`
5. `jt -t monokai -T`
6. Extensions I like:
   1. Hinterland
   2. Autopep8
   3. Codefolding