# Notes
Notes

1. Python notes for everyone

Generators
Convenient way to implement the iterator protocol.

def count(start, step):
    while True:
        yield start
        start += step
>>> counter = count(10, 2)
>>> next(counter), next(counter), next(counter)
(10, 12, 14)


Importing packages
Python packages are a collection of useful tools developed by the open-source community. They extend the capabilities of the python language. To install a new package (for example, pandas), you can go to your command prompt and type in pip install pandas. Once a package is installed, you can import it as follows.

testin one two one two
