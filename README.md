# python-tutoring

 * [Introduction](#introduction)
 * [Installing python](#installing-Python)
 * [Accessing python](#accessing-python)
   * Hello world - Python shell
 * [Finding help](#finding-help)
   * python documentation
   * other resources?
 * Variables
   * assigning, accessing, manipulating
 * Datatypes I
   * strings, integers, floats
 * Input / Output

`2020-03-14`
---------------------------------
 * Conditionals ("if" statements)
 * Datatypes II
   * lists, dicts
 * Loops
    * "for" loops
    * "while" loops
 * functions
 * objects
 * modules and imports
 * pip, virtualenv and 3rd party libraries

## Introduction

First released in 1991
Current version is 3.8.2
Older Versions (2.7) are still arround but should not be used anymore (End Of Life Jan 1 2020).
There are a lot of differences between python 2.7 and python 3 and its not worth your time to learn

One of the most popular languages in the world
Use

## Installing Python

https://www.python.org/downloads/

## Accessing Python

 * Text Editor
    * IDLE (Default python editor and runner, easy, very minimal, not pretty to look at)
    * Visual Studio Code (**recommended** - best allround in my opinion)
    * Atom (simple, extensible)
 * IDE (Interactive Development Evnironment
    * pycharm (Most features - often over the top for python)
    * Wing IDE (Not as powerful as most IDE's, not as simple as most text editors
 * cmd (command line)

<details>
  <summary>Recommended Minimal VSCode Settings for Python
</summary>
 ```json
 {
    "editor.renderWhitespace": "all",
    "editor.rulers": [79],
    "files.autoSave": "afterDelay",
    "files.exclude": {
        "**/*.pyc": true,
        "**/__pycache__": true
    },
    "python.linting.flake8Enabled": true,
    "python.autoComplete.addBrackets": true,
    "workbench.tree.indent": 16,
}
```
</details>


## Hello World

Open python IDLE and you should be presented with a mostly blank window with some text at the top.

```
Python 3.8.2 (tags/v3.8.2:7b3ab59, Feb 25 2020, 22:45:29) [MSC v.1916 32 bit (Intel)] on win32
Type "help", "copyright", "credits" or "license()" for more information.
>>> 
```


## Finding Help

Your best bet is to google and look for search results which come from these pages.

 * Python documentation (https://docs.python.org/3/)
 * Stack Overflow (https://stackoverflow.com/)

Be careful with results from 'tutorialspoint', 'w3schools' as they can sometimes give incomplete or incorrect advice.

Answers on Stack Overflow can also be incomplete or incorrect but due to users being able to upvote and downvote and comment on answers, it's often apparent if the answer is good or bad.

## 

## Glossary

|||
|---|---|
|Text Editor|A program such as notepad, notepad++ or atom which alows you you edit code files|
|IDE|Interactive Development Environment|
|Shell|Text only user inteface for interacting with a system or service.|
|Syntax|the structure of statements in a computer language|
