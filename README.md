# Maze Documentation
This repository holds the documentation for Clojure Project Maze.

Hosted on ReadTheDocs: [![Documentation Status](https://readthedocs.org/projects/maze-documentation/badge/?version=latest)](https://maze-documentation.readthedocs.io/en/latest/?badge=latest)

Please visit: https://maze-documentation.readthedocs.io/en/latest/

## Building the document
First, install Python 3 and execute the command below.
```
pip install -r requirements.txt
```

Then, the HTML version can be built with
```
make html           # For Linux
./make.bat html     # For Windows
```

The LaTeX version can be built with
```
make latex          # For Linux
./make.bat html     # For Windows
```