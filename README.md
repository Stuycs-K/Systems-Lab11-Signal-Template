# Lab - Signals

Write a C program with the following features:

## Loop forever

* Runs constantly inside a forever while loop.
    
* Print out the process' PID inside the loop.
    
* Use the sleep(1) function to have the program wait 1 second between inner loop iterations.
    
## Catch the following signals

SIGINT

* Before exiting, do two things:
    
  1. Print to stdout "Process with PID: XXX Exiting due to SIGINT" replacing XXX with the actual process id.
  2. Append the above message to a file output.txt

SIGQUIT 

* Print out the PID and Parent PID in the format: "PPID: XXX , PID: YYY" replacing XXX and YYY with the correct ID values.
* DO NOT cause the program to exit.
    
## Running the program and testing:

Include a makefile with a run and compile target.
    
After running your program I will use the kill command (or keyboard shortcuts) to send signals to your program.

