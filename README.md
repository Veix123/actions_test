# robotont.github.io
[Documentation](robotont.github.io) for robotont

## Updating docs

##### Update apt and pip
```
sudo apt update
pip3 install --upgrade pip
```

##### Getting dependencies
```
sudo apt install python3-sphinx
pip3 install sphinx_rtd_theme
```

* Make whatever changes you need to the docs files in `source/`
* Run `make html` to generate new docs
