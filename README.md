# FSIM

This repository provides an example of the fault simulator, FSIM.

## Environment 

- Ubuntu 22.04

- C++17

- Boost 1.84

# USAGE

Before run the FSIM, make sure all files are in (UNIX)LF format.

To run the **FSIM** , simply execute

```
./FSIM  testcase/asic_top  lib/sky130.json
```

Then asic_top.det and asic_top.udet will be created in fold testcase, which contains the detected and undetected faults.