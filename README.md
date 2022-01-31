# Disk-Scheduling-Simulator
Disk Scheduling Simulator

READ ME FILE
-------------

1) Run the command for make file- make -f makefile
2) Run ./simdisk


Usage
-----------

1) printf("\n Usage Summary - simdisk [-h] [-n number-of-cylinders] [-d disk-shed-policy] [-i input file]\n");
2) printf("OPTIONS:\n");
3) printf("-h\t: Print a usage summary with all options and exit.\n");
4) printf("-n number-of-cylinders\t: Set the total number cylinders on the disk. By default it should be 200.\n");
5) printf("-d disk-shed-policy\t: Set the disk scheduling policy. It can be either FCFS (First-come-first-served), SSTF (Shortest-seek-time-first), C-SCAN, or LOOK. The default will be FCFS. Assume at the t=t0, the disk was moving from 0 towards other end of the disk.\n");
6) printf("-i input file\t: Read the request sequence from a specified file. If not given, the sequence should be read from STDIN (ended with ENTER).\n");
