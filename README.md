```python
PIP_MODULES := \
	cryptography==3.3.2 \
	future==0.18.2 \
	lockfile==0.8 \
	python-daemon==1.5.1 \
	pytz==2021.1 \
	filelock==3.0.12 \
	djangorestframework==3.9.4
```
## For hue_python_modules.tar.gz
https://github.com/bhagadepravin/download/blob/main/hue_python_modules.tar.gz
```python
tar -xvzf hue_python_modules.tar.gz
cd hue_python_modules
pip install --no-index --find-links=./ enum34 cryptography==3.3.2  future==0.18.2 lockfile==0.8 python-daemon==1.5.1 pytz==2021.1  filelock==3.0.12 djangorestframework==3.9.4
```


## For hue_python_modules_1.tar.gz
https://github.com/bhagadepravin/download/blob/main/hue_python_modules_1.tar.gz

```python
tar -xvzf hue_python_modules_1.tar.gz
cd hue_python_modules_1
pip install --no-index --find-links=./ setuptools-scm==1.11.1 pytest-django==3.10.0  pytest==3.6 
```



```python
======================
$ pip install --no-index --find-links=./ enum34 cryptography==3.3.2  future==0.18.2 lockfile==0.8 python-daemon==1.5.1 pytz==2021.1  filelock==3.0.12 djangorestframework==3.9.4
Ignoring indexes: https://pypi.python.org/simple
Collecting enum34
Collecting cryptography==3.3.2
Collecting future==0.18.2
Collecting lockfile==0.8
Collecting python-daemon==1.5.1
Collecting pytz==2021.1
Collecting filelock==3.0.12
Collecting djangorestframework==3.9.4
Requirement already satisfied (use --upgrade to upgrade): six>=1.4.1 in /usr/lib/python2.7/site-packages (from cryptography==3.3.2)
Collecting cffi>=1.12 (from cryptography==3.3.2)
Requirement already satisfied (use --upgrade to upgrade): ipaddress; python_version < "3" in /usr/lib/python2.7/site-packages (from cryptography==3.3.2)
Requirement already satisfied (use --upgrade to upgrade): setuptools in /usr/lib/python2.7/site-packages (from python-daemon==1.5.1)
Collecting pycparser (from cffi>=1.12->cryptography==3.3.2)
Installing collected packages: enum34, pycparser, cffi, cryptography, future, lockfile, python-daemon, pytz, filelock, djangorestframework
  Running setup.py install for future ... done
  Running setup.py install for lockfile ... done
  Running setup.py install for python-daemon ... done
  Running setup.py install for filelock ... done
Successfully installed cffi-1.15.1 cryptography-3.3.2 djangorestframework-3.9.4 enum34-1.1.10 filelock-3.0.12 future-0.18.2 lockfile-0.8 pycparser-2.21 python-daemon-1.5.1 pytz-2021.1
============================
$ pip install --no-index --find-links=./ setuptools-scm==1.11.1 pytest-django==3.10.0  pytest==3.6
Ignoring indexes: https://pypi.python.org/simple
Requirement already satisfied (use --upgrade to upgrade): setuptools-scm==1.11.1 in /usr/lib/python2.7/site-packages
Requirement already satisfied (use --upgrade to upgrade): pytest-django==3.10.0 in /usr/lib/python2.7/site-packages
Requirement already satisfied (use --upgrade to upgrade): pytest==3.6 in /usr/lib/python2.7/site-packages
Requirement already satisfied (use --upgrade to upgrade): pathlib2; python_version < "3.4" in /usr/lib/python2.7/site-packages (from pytest-django==3.10.0)
Requirement already satisfied (use --upgrade to upgrade): atomicwrites>=1.0 in /usr/lib/python2.7/site-packages (from pytest==3.6)
Requirement already satisfied (use --upgrade to upgrade): py>=1.5.0 in /usr/lib/python2.7/site-packages (from pytest==3.6)
Requirement already satisfied (use --upgrade to upgrade): setuptools in /usr/lib/python2.7/site-packages (from pytest==3.6)
Requirement already satisfied (use --upgrade to upgrade): six>=1.10.0 in /usr/lib/python2.7/site-packages (from pytest==3.6)
Requirement already satisfied (use --upgrade to upgrade): more-itertools>=4.0.0 in /usr/lib/python2.7/site-packages (from pytest==3.6)
Requirement already satisfied (use --upgrade to upgrade): funcsigs; python_version < "3.0" in /usr/lib/python2.7/site-packages (from pytest==3.6)
Requirement already satisfied (use --upgrade to upgrade): attrs>=17.4.0 in /usr/lib/python2.7/site-packages (from pytest==3.6)
Requirement already satisfied (use --upgrade to upgrade): pluggy<0.7,>=0.5 in /usr/lib/python2.7/site-packages (from pytest==3.6)
Requirement already satisfied (use --upgrade to upgrade): scandir; python_version < "3.5" in /usr/lib64/python2.7/site-packages (from pathlib2; python_version < "3.4"->pytest-django==3.10.0)
Requirement already satisfied (use --upgrade to upgrade): ordereddict in /usr/lib/python2.7/site-packages (from funcsigs; python_version < "3.0"->pytest==3.6)
```
