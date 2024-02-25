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
