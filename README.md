# neo4j-jupyter

Jupyter Notebook forked from [nicolewhite/neo4j-jupyter](http://nicolewhite.github.io/neo4j-jupyter)

use of py2neo python driver and neo4jupyther repository to display graphs in the notebooks using vis.js

## Packages configuration
1. check if pipenv is installed in your computer

    ```pipenv --version```

2. If it is not installed run `pip install pipenv` or `pip3 install pipenv`
3. In the terminal working directory run `pipenv install`
4. Select the Python3.8.5 interpreter
5. Change the file `.vscode/settings.json` the field **"python.pythonPath":** with the source of your python.exe

Check this [Youtube Tutorial](https://www.youtube.com/watch?v=5HUL5lWkEyg) for more information. For more information about using virtualenv in VS Code check this [page](https://code.visualstudio.com/docs/python/environments)

## Running notebooks
1. Have an active database session of neo4j-Desktop
2. Change the `"username"` and `"password"` from the first code block of the notebook (it might be also needed to change the "DATABASE_URI")"
3. Use the VS Code extension Jupyter to run the notebook.
4. Alternatively, it is also possible to run Jupyter in your computer following this documentation 
    * run the notebook using the command `python -m notebook` in the terminal of the directory. It should open a window in your browser with the notebooks.
