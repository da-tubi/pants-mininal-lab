# Template project for Python projects using Pants with JupyterLab support

This is a minimal template project using Pants:
+ No subproject
+ Only one fixed set of python dependencies
+ With IDE support
+ With JupyterLab support

For demo project with multiple subprojects and dependencies sets, see [pants-pyspark](https://github.com/da-tubi/pants-pyspark).

## How to launch jupyterlab
```
bin/lab
```

## VSCode/PyCharm Integration
```
./pants export ::
```
Here is the Python interpreter generated by the above export command:
```
dist/export/python/virtualenvs/python-default/3.8.14/bin/python
```

For VSCode, a sample [.vscode/settings.json](.vscode/settings.json) with Python `3.8.14` is prepared for you.

For PyCharm, please click `PyCharm -> Preferences... -> Project: pants-minimal-lab -> Python Interpreter` to add the existing `Virtualenv Environment` and then select it.
