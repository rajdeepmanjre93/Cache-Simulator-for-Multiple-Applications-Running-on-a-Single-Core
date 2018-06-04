README

Usage:
1. Compiling the codes: (For Round Robin and First Come First Served)

>> gcc cache_sim_rr.c -o cache_sim_rr -lm
>> gcc cache_sim_fcfs.c -o cache_sim_fcfs -lm

2. Executing the code: (For Round Robin)
Usage: ./cache_sim_rr [cache size: 32768] [block size: 8|32|128] [cache mapping: dm|fa] [cache organization: uc]

>> ./cache_sim_rr 32768 8 dm uc
>> ./cache_sim_rr 32768 8 fa uc

Change block size from 8, 32, 64, 128….32768.

2. Executing the code: (For First Come First Served)
Usage: ./cache_sim_fcfs [cache size: 32768] [blocksize: 8|32|128] [cache mapping: dm|fa] [cache organization: uc]

>> ./cache_sim_fcfs 32768 8 dm uc
>> ./cache_sim_fcfs 32768 8 fa uc

Change block size from 8, 32, 64, 128….32768.