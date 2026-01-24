# Camera Problems & Fixes (Unipod)


## Problem: `libcamera-hello: command not found`


### Cause


libcamera was built from source, but `/usr/local/lib/aarch64-linux-gnu` was not in the runtime linker path.


### Official Docs Status


❌ Not mentioned in TurtleBot3 documentation


### Fix


```bash
export LD_LIBRARY_PATH=/usr/local/lib/aarch64-linux-gnu:$LD_LIBRARY_PATH