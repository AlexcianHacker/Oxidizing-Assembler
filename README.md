# Oxidizing Assembler
Oxidizing Assembler, Or Oxidized Assembler, Is An Assembler With Rust Safety Checks (Ownership, Borrow Checking, Etc.) <br> 




## Contributions & Pull Requests 

- This Project Is Open To Collaboration From Anyone, Feel Free To Contribute <br> 




## Origin && Progress 

- This Particular Idea Of An Oxidizing Assembler Originated From Alex In June 2026. Later In Late July 2026, The Idea Surfaced During A Discussion Between Alex And His Friend About Low-Level Programming, Where It Was Agreed To Collaborate On Creating The Specification And Implememtation Of The Oxidizing Assembler. 
- This Project Is Very New, And The Concept Of Rust Memory Safety (And Memory Safety In General) In Assembly Is Generally Uncharted Waters. Therefore The Project Is Considered Highly Experimental For The Time Being, And Will Stay That Way For The Foreseeable Future. 




## Repositories 

- Project Will Be Mirrored On Codeberg At Some Point In Time. 




## Architectures 

<br> 
Project Will Attempt To Support The Following Architectures (Primary): <br>
- x64 / AMD64 (x86_64 / Intel64) <br>
- ARM64 / AArch64 <br> 
- RISC-V (RV64, RV32) <br> 
- PowerPC64 / Power64 (Power ISA / OpenPOWER) <br> 
- MIPS64 <br> 
- SPARC64 <br> 

<br> 
Secondary Support Will Attempt To Be Given To The Following Architectures: <br> 
- x86 / IA-32 (i386 / i686) <br> 
- ARM32 / AArch32 <br> 
- PowerPC32 / Power32 <br> 
- MIPS32 <br> 
- SPARC32 <br> 

<br> 
Tertiary Support - Any Contributions Are Welcomed But No Other Attempt Will Be Made To Support The Following Architectures: <br> 
- Intel Itanium (IA-64) <br> 
- Z/Architecture (S390x / IBM Z) <br> 


## OXIDIZING ASSEMBLER SPECIFICATION V0.0.3 (ALPHA) 



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



