# DLL Injector Assignment

## Overview
This project includes a DLL injector designed to inject a DLL into a 64-bit target process with minimal detection probability.

## Source Code
- `injector.cpp`: The main injector code.
- `dll_injector.h`: Header file for the injector.
- `documentation.txt`: Document detailing stealth techniques.

## Compilation
To compile the code, use the following command:
```bash
g++ injector.cpp -o injector

Running
Run the injector with the process ID and DLL path as arguments:
./injector <PID> <DLL_PATH>