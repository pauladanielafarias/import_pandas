# 1. Installing Python 3

### Installing on Mac OS X

1. Install [Homebrew](https://brew.sh/#install)

```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2. Install Python 3

```
$ brew install python
```

3. See the version to check that Python 3 is installed

```
$ python3 --version
```


# 2. Installing Python packages and libraries

- Before installing any package or library, make sure that your pip version is up-to-date. 

```
pip install --upgrade pip
pip --version
```

or

```
python -m pip install -U pip
-m pip --version
```

- You can list all the installed packages in your machine, including editables: 

```
pip list
```
[pip documentation - pip list](https://pip.pypa.io/en/stable/reference/pip_list/)

- If you want to know more about an installed package in your machine:

```
pip show pkg-name
```

_Instead of ```pkg-name``` type the name of the package you want to show._

#### If you need to [install pip manually](https://pip.pypa.io/en/stable/installing/) (you also need [python3](https://www.python.org/downloads/)):

1. Download [get-pip.py](https://bootstrap.pypa.io/get-pip.py) or use curl: ``` curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py ```
2. Run the following command in the folder where you have downloaded get-pip.py: ```python3 get-pip.py```


# Some Python packages and libraries:
Sometimes ```pip``` is invoked by an old script wrapper, to avoid this problem you can invoke Python with ```-m pip``` instead of running ```pip``` directly.

## 1. Installing os-sys
[os-sys](https://pypi.org/project/os-sys/)

```
pip install os-sys
```
This command downloads:
- os-sys
  - pandas
  - mysql-connector
  - pyyaml
  - progressbar
  - mathparse
  - pygubu
  - PyInstaller
  - pint
  - cefpython3
  - tqdm
  - pytest
  - wifi
  - netifaces
  - extract-zip
  - pyspeedtest
  - pypiwin32
  - geocoder
  - os-sys-php
  - nltk
  - progress
  - auto-py-to-exe
  - pythonGui
  - beautifulsoup4
  - matplotlib (will need the requirement: text-editor)
  - numpy
  - pytz
  - sqlalchemy
  - requests
  - os-sys
  - webview

## 2. Installing wget
[wget](https://pypi.org/project/wget/)

```
pip install wget
```


## 3. Installing pandas
[pandas](https://pypi.org/project/pandas/)

```
pip install pandas
```


## 4. Installing matplotlib
[matplotlib](https://pypi.org/project/matplotlib/)

```
pip install matplotlib
```

## 5. Installing numpy
[numpy](https://pypi.org/project/numpy/)

```
pip install numpy
```


## 6. Installing tensorflow
[tensorflow](https://pypi.org/project/tensorflow/)

```
pip install tensorflow
```

## 7. Installing OpenCV
[OpenCV](https://pypi.org/project/mtcnn-opencv/)

```
#requires numpy: pip install numpy

pip install opencv-python
```
[OpenCV Documentation](https://docs.opencv.org/master/)
Usage:
```
import cv2
```

## 8. Installing fuzzywuzzy
[fuzzywuzzy](https://pypi.org/project/fuzzywuzzy/)

```
pip install fuzzywuzzy
```
Usage:

```
 from fuzzywuzzy import fuzz
 from fuzzywuzzy import process
 ```
 
 ## 9. Installing Jupyter Notebook & Jupyter Lab
[jupyter](https://jupyter.readthedocs.io/en/latest/install/notebook-classic.html)
[jupyterlab](https://jupyterlab.readthedocs.io/en/latest/getting_started/installation.html)

```
pip install jupyter
pip install jupyterlab
```
