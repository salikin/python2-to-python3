# Ubuntu 18.04 Converting Python2 to Python3

This is a quick guide for converting Python2 to Python3 script. Refer to https://stackoverflow.com/questions/31228927/how-to-use-install-python-2to3

You need to first install the following packages:

apt install 2to3

apt install python3-lib2to3

apt install python3-toolz

Then, You can simply go to that directory your python file is in and type the following command:

2to3 ./filename.py

OR

2to3 . -w

This last will convert all the python files that are in the directory.
