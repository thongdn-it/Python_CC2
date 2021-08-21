# Chapter 1:  Getting Started

## Install Python on MacOS

### Checking installed Python version

Open terminal, enter `python --version`, and then press Enter.

```sh
python --version
```

or you can enter `python3 --version` to checking whether Python 3 is install.

```sh
python3 --version
```

### Install Python 3

If Python 3 isn't installed, you'll need to install it, because in this book use the *python3 command*. You'll run into trouble trying to run the code in this book using Python 2.

- Install form website:

You can find latest version of Python at [https://www.python.org/downloads][python_download]. After the file downloads, run the installer. When you're finished, you can run `python3 --version` to check version.

- Install via [brew]:

```sh
brew install python
```

## Install Editor

In the book, The author suggests using [Sublime Text][slt] but you can use any other text editor and IDEs. E.g: [Visual Studio Code][vsc], [Atom][atom], [PyCharm][pyc]...

In my case, i using Visual Studio Code. You can follow below step to install Visual Studio Code for Python:

- Install [Visual Studio Code][vsc]

- Install [Python extension][python_vsc] for Visual Studio Code. It is strong extension for Python, supports IntelliSense (Pylance), Linting, Debugging (multi-threaded, remote), Jupyter Notebooks, code formatting, refactoring, unit tests, and more.

## Running a Hello World Program

You create new file with name `hello_world.py` with content:

```python
print('Hello World')
```

The extension *.py* tells that the code in your file is written in Python. When in this file, you can run your program by selecting ***Run > Start Debug(F5)*** or ***Run > Run Without Debug(^ F5)***.

A terminal screen should appear at bottom of Visual Studio Code window, showing the following output:

```python
Hello World
```

> ## Summary
>
> In this chapter, you learn a bit about Python in general, and you installed Python on your system (MacOS).
> You also installed a text editor to make it easier to write Python code.

[//]: # (reference links)
[python_download]: https://www.python.org/downloads
[brew]: https://brew.sh/#install
[slt]: https://www.sublimetext.com
[vsc]: https://code.visualstudio.com
[atom]: https://atom.io
[pyc]: https://www.jetbrains.com/pycharm
[python_vsc]: https://marketplace.visualstudio.com/items?itemName=ms-python.python
