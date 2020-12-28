WebDriver in Python
=====

# How to setup Python3 for this project

## prerequisite

- will use macOS Catalina
- homebrew is already installed
- IntelliJ IDEA is already installed


## story

- will install Python3 to macOS
- will create a virtual environment for this project using venv
- will install Numpy and other libraries into the virtual invrionment for this project

## procedure

### install Python3

```
$ brew update
```

```
$ brew install python3
...
$ pthyon3 -V
```

### create a virtual env for this project

```
$ cd ~/github/SelfTaughtPyton
$ python3 -m venv venv
```

```
$ source venv/bin/activate
```

```
$ python -V
```

### install Numpy and Matplotlib

```
$ pip install numpy
$ pip install matplotlib
```

### setup IntelliJ IDEA Project's Python SDK

#### Install Python Plugin into IDEA

IntelliJ IDEA Preferences > plugins > Python

#### setup Platform SDK for the project
File > Project Structure > Platform SDK

# MacにPythonをインストールしこのプロジェクトに仮想環境を作ってjupyter notebookを起動するまで

https://qiita.com/Yanagawa_Yoshihisa/items/35e6f70a8411277282ce
