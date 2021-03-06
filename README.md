<p align="center">
  <a href=#>
    <img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/263/HBTN-hbnb-Final.png" alt="Holberton School HBnB logo">
  </a>
</p>

# HBnB
_Holberton School Air BnB clone_

## Table of Contents
* [About](#about)
* [The Console](#the-console)
* [Web Static](#web-static)
* [Authors](#authors)

## About
HBnB is a clone of Air BnB. The project is divided into 7 parts:
1. The console
2. Web Static
3. MySQL
4. Fabric
5. Flask
6. REST API
7. Web dynamic

## The Console

The Console is the first part of the HBnB clone. In it, we wrote classes for representing users and listings, a file storage engine for saving and recalling data between interactive sessions, as well as a command interpreter for easily managing our data.

### HBnB CLI — The command interpreter

The HBnB CLI (command line interpreter) provides a convenient command line interface specifically to manage (add, delete, modify, etc.) HBnB data.
It offers an imporved workflow over alternatives such as embedding data in the source code, manually managing a data file, or using the Python interpreter to manage the data.

### Commands
* `all [CLASS]` - Show all objects.
* `create CLASS` - Create a new object.
* `destroy CLASS ID` - Destroy a specified instance.
* `help [COMMAND]` - Get information about a command.
* `quit` - Close an interactive session. Also quit with `^-D` or `EOF`.
* `show CLASS ID` - Display a single instance.
* `update CLASS ID ATTRIBUTE VALUE` - Edit attributes of an instance.

### Usage

Start an interactive HBnB CLI session by executing `console.py`:

`./console.py`

If it runs sucessfully, it will display the prompt and await input:

`(hbnb) `

Simply type any valid command(s) listed above. Type `quit` to exit the interactive session.

The HBnB CLI may also be used non-interacively by piping input to it from a shell:

`$ echo "help" | ./console.py`


### Examples
```
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  all  create  destroy  help  quit  show  update

(hbnb) create Place
aba364fd-8b9e-4c4b-b865-8db6a6e9bc03

(hbnb) all
["[Place] (aba364fd-8b9e-4c4b-b865-8db6a6e9bc03) {'created_at': datetime.datetime(2021, 7, 1, 13, 29, 27, 264673), 'id': 'aba364fd-8b9e-4c4b-b865-8db6a6e9bc03', 'updated_at': datetime.datetime(2021, 7, 1, 13, 29, 27, 264832)}"]
(hbnb) 
```

## Web Static

The Web Static part of this project consisted of designing the website HTML and CSS.

## Authors
Justin Masayda [@keysmusician](https://github.com/keysmusician)

Carson Stearn [@krytech](https://github.com/krytech)
