def printIncreasingPower(x):
    """
    Prints the squares of numbers from 1 up to the point where the square
    is less than or equal to x.

    Args:
        x: A positive integer (2 <= x <= 10^3).
    """
    i = 1
    while i * i <= x:
        print(i * i)
        i += 1
