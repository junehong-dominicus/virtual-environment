## pip
#### Install a package
```pip install <package_name>```
#### Upgrade a package
```pip install --upgrade <package_name>```
#### Uninstall a package
```pip uninstall <package_name>```
#### List installed packages
```pip list```
#### Show installed package's information
```pip show <package_name>```



## To install a Python package from its source code
- Open a terminal or command prompt and navigate to the root directory of the extracted source code. This directory typically contains a __setup.py__ file.
- Install in Editable Mode (Recommended for Development) ```python3 -m pip install -e . ```
- Install in Standard Mode ```python3 -m pip install . ```
- Alternatively, if the package uses setuptools and you want to install it directly without pip, you can use setup.py ```python3 setup.py install```
