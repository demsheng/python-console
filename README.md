python-console
=====
fork from https://github.com/alextsui05/python-console

- ubuntu 16.04
- Qt 4.8.7
- python 2.7.12

install
-------

1. config
```
sudo apt-get install build-essential
sudo apt-get install qt4-dev-tools qt4-doc qt4-qtconfig qt4-demos qt4-designer qtcreator
sudo apt-get install python2.7-dev
sudo apt-get install libboost-dev
```
2. compile
```
mkdir build
cd build
cmake ..
make
```



python-console
=====
This is the result of a small side project to write a Qt widget that
encapsulates an interactive Python shell.

Quickstart
-----
You should have Qt4 and Python libraries. You will need CMake to build this
project as follows:

1. mkdir build
2. cmake ..
3. make

License
-----
This project is licensed under the [MIT](http://opensource.org/licenses/MIT) license.
