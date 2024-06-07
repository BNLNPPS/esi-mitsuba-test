# Notebooks

In the start, this is just a folder for keeping and tweaking notebooks obtained from
the "Quick Start" page of Mitsuba documentation.


# Initial Testing

Tested with the following rendering options:
* CPU (scalar)
* CPU (vector)
* GPU (CUDA)

# LLVM

By default, the LLVM library may not be found on platforms like ROcky, so if this (CPU) functionality is needed,
one needs to point to it directly (as en example - this may vary by the platform):

```bash
export DRJIT_LIBLLVM_PATH=/usr/lib64/libLLVM-16.so
```

