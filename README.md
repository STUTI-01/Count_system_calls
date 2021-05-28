# Count_system_calls

It is a simple program that counts the number of system calls used by any application and summarizes the result at the end. The summary includes stating about the most frequently used applications across applications, most infrequently used system calls, time spent in locking and threads created by each process.

How to run?

Required tools (On Ubuntu 18.04):
Wireshark 
Systemtap
Matplotlib
Redis-server

How to run?
gcc trace_programs.c
python3 get_result.py)
topsys.stp can be run in another terminal simultaneously (however, it's just an additional feature and not a requirement)
