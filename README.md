# Brasserie App

This project implements a Restaurant Recommendation System.
The search algorithm used here is a __content-based-filtering__ technique, which takes city, locality and restaurant name and generates a similarity score index. The search results would then be shown based on the generated similarity score index .

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

The libraries that you need to run the program and how to install them:

```
1. PyQt5
2. NLTK
3. pandas
5. sklearn
5. numpy
```

### Installing

A step by step series of commands that will help your development env running.

Use Python 3.7 :

```
pip install pyqt5
pip install pyqt5-tools
pip install nltk
pip install sklearn
```

After Installing ntlk, do:

```
import nltk
nltk.download()
```

Download all the data shown.


## Running the program

Just open your terminal, head to cloned directory, do:

```
python Brasserie-App.py
```

Note: __/python__ must be added to your system's Global path

### Using Brasserie App

To get a recommendation from the app, the user can follow two pathways:

```
1. By Entering the Restaurant Details (like city, locality and restaurant name).
2. By Selecting one of the Top Recommended Restaurant.
```

After entering the details above specified, the user will be given its recommendation by searching and generating a
similarity score index, and the top five recommendations will be shown.


## Built With

* [PyQt5](https://pypi.org/project/PyQt5/) - The GUI framework used

## Authors

* **Nishant Pandey** - [unexh](https://github.com/unexh)
* **Sehajbir Thind** - [SehajbirThind](https://github.com/SehajbirThind)
