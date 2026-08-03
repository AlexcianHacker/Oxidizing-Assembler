# Oxidizing-Assembler
Oxidizing Assembler, Or Oxidized Assembler, Is An Assembler With Rust Safety Checks (Ownership, Borrow Checking, Etc.) 




## OXIDIZING ASSEMBLER SPECIFICATION V0.0.1 (ALPHA) 



### OPTIMIZATIONS 

- The Assembler Can Be Set To Achieve Optimizations Of Varying Levels Using The -O Flag, With Values Between 0 (No Optimizations Whatsoever) And 9 (All The Most Arcane, Herculean, Platform Specific Optimizations Available). The Default Is -O3. 


### MACROS 

- Macros Can Be Turned On/Off With The -m Flag. 


### BUILD MODES 

- Build Modes Exist To Enable Or Disable Safety Measures. There’s Several Possible Modes, While The Default Is With All Safety Measures Enabled. 


### JOBS 

- Similar To Most Compilers, The Amount Of Build Threads Can Be Set With The -j Flag. On A System With Less Than 6 Cores, The Default Is One Thread. On A System With 6+ Cores, The Default Is 2 Threads. 


### LINKING 

- Linking Other Binaries Can Be Done With The Standard -l Flag.


### OUTPUT FILE 

- Like GCC, A Custom Output File Can Be Set With The -o Or -of Flag. 



