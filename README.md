# Lab - Signals

Write a C program with the following features:

## Loop forever

Runs constantly inside a forever while loop.
    
Print out the process' PID inside the loop.
    
Use the sleep(1) function to have the program wait 1 second between inner loop iterations.
    
## Catch the following signals

SIGINT

.* Before exiting, do two things:
    
.* Print to stdout "Process with PID: XXX Exiting due to SIGINT" replacing XXX with the actual process id.
    
.* Append the above message to a file output.txt

SIGUSR1 

    Print out the PID and Parent PID in the format: "PPID: XXX , PID: YYY" replacing XXX and YYY with the correct ID values. DO NOT cause the program to exit.
    
    As always include a makefile with a run and compile target.
    
    I will make compile and then make run. I will then use the kill command to send signals to your program.
