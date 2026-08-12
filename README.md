# Oxidizing Assembler
Oxidizing Assembler, Or Oxidized Assembler, Is An Assembler With Rust Safety Checks (Ownership, Borrow Checking, Etc.) <br> 




## Contributions & Pull Requests 

- This Project Is Open To Collaboration From Anyone, Feel Free To Contribute <br> 




## Origin && Progress 

- This Particular Idea Of An Oxidizing Assembler Originated From Alex In June 2026. Later In Late July 2026, The Idea Surfaced During A Discussion Between Alex And His Friend About Low-Level Programming, Where It Was Agreed To Collaborate On Creating The Specification And Implememtation Of The Oxidizing Assembler. 




## Repositories 

- Project Will Be Mirrored On Codeberg At Some Point In Time. 




## Architectures 

<br> 
Project Will Attempt To Support The Following Architectures (Primary): 
- x64 / AMD64 (x86_64 / Intel64) 
- ARM64 / AArch64 
- RISC-V (RV64, RV32) 
- PowerPC64 / Power64 (Power ISA / OpenPOWER) 
- MIPS64 
- SPARC64 

Secondary Support Will Attempt To Be Given To The Following Architectures: 
- x86 / IA-32 (i386 / i686) 
- ARM32 / AArch32 
- PowerPC32 / Power32 
- MIPS32 
- SPARC32 

<br> 
Tertiary Support - Any Contributions Are Welcomed But No Other Attempt Will Be Made To Support The Following Architectures: 
- Intel Itanium (IA-64) 
- Z/Architecture (S390x / IBM Z) 


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


### FILENAME EXTENSION 

- Will Use Filename Extensions `.oasm`, `.oxs`, `.oxS` 



