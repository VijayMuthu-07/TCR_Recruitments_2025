# TCR_Recruitments_2025
Round-1 Quiz

The error was due to improper function call syntax in b.py.

All top-level code in a python file gets executed when its is imported by another file, that's why print statement from c.py was executed while a.py was executed. Now that the print statement is under (if __name__ == "__main__":) it will only be executed if c.py is directly executed.
