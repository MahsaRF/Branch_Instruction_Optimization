# Branch Instruction Optimization

Branch Instruction Optimization

•	Analyzed the branch instruction performance for different branch instruction in the program with different input dataset sizes utilizing PAPI library in C

•	Implemented the branch optimizations using the gcc macros likely/unlikely in the branch condition section to reduce the number of mispredictions



Instrumented the code to measure the number of branch instructions 
(PAPI_BR_INS) and the number of mispredictions (PAPI_BR_MSP) for the branch instructions
in the following three functions and implemented the branch optimizations using the gcc macros 
likely/unlikely in the branch condition section to reduce the number of mispredictions

– function: minmax_filter_timings

– function: minmax_calc_per_iteration

– function: minmax_calc_statistics

•	Skills used: C, PAPI, gprof tool

This project was submitted as part of the Advanced Computer Architecture course taught by Professor Edgar Gabriel at the University of Houston Spring 2020


