## Issues happend
Run the command for install the py scripts: 
```bash
python install.py
```

Then, it display the error message: 
```bash
usage: install.py [-h] --onnxruntime {default} [--skip-conda] [-v]
install.py: error: the following arguments are required: --onnxruntime
```

## Why happened?
The error message indicates that the install.py script expects a mandatory argument --onnxruntime.

## Solution
Run the script with the required argument:
```bash
python install.py --onnxruntime default
```
