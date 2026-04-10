# Compx234- readers-writers-lab2
This project uses the threading module and condition variables in Python 3 to implement the classic Readers-Writers synchronization problem in a monitor-style design, ensuring safe access to shared resources.
Implementation Rules
Multiple readers can read at the same time
Writers must have exclusive access to the resource
Mutual exclusion between readers and writers; mutual exclusion between writers
File List
readers_writers.py: Complete program code
README.md: Project documentation
How to Run
Ensure Python 3 is installed
Run in the terminal:
python readers_writers.py
Sample Output
Reader 1 is waiting to read
Reader 1 starts reading. Active readers: 1
Reader 2 starts reading. Active readers: 2
Reader 1 stops reading
Reader 2 stops reading
Writer 1 starts writing
Writer 1 stops writing
All threads completed successfully
Author Information
Name: liu xin yang
Course: COMPX234
Lab: Assignment 2

