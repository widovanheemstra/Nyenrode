# Install instructions Python/Jupyter notebook

## Mac Install
First we will install the latest version of python 2.7.11.
Then we create a virtual environment and setup all necessary packages

1. Download and install python for [Mac OS X 64-bit/32-bit installer](https://www.python.org/ftp/python/2.7.11/python-2.7.11-macosx10.6.pkg)
2. Install VirtualEnv by running the following command in Terminal. If you run into problems, try with 'sudo':
```
$ pip install virtualenv
```

3. Create a virtual environment in your user space, by running the following commands:
```
$ cd ~/
$ mkdir virtualenvs
$ cd virtualenvs
$ virtualenv datascience
$ cd datascience

[Keep terminal screen open]
```
4. Download the file containing a list of required packages and place it in the 'datascience folder': [requirements.txt](https://github.com/widovanheemstra/Nyenrode/blob/master/requirements.txt)

5. Return to your terminal screen and run the following commands:
```
$ source bin/activate
$ pip install -r requirements.txt
```

6. Now we can launch the Jupyter Notebook by running the following command:
```
$ jupyter notebook
```

7. A browser window is launched showing your home folder of your Notebooks.

8. If you want to exit Jupyter type ctrl+c twice
9. If you want to deactivate the python virtualenv type:
```
$ deactivate
```

## Windows install
1. Download the WinPython distribution (32bit or 64bit) from: (https://sourceforge.net/projects/winpython/files/WinPython_2.7/2.7.10.3/)
2. Run the downloaded file and follow the install instructions
3. Navigate to the install location in your Explorer
4. Double click the Jupyter executable
5. A browser is launched and showing your home folder of your Notebooks.