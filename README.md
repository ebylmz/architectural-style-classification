# 🏛️ Architectural Style Classification

## Build

Package the project
```bash
pip install --editable .
```

Create virtual environment
```bash
conda create -n arch
```

Activate virtual environment
```bash
conda activate arch
```

Install dependencies
```bash
pip install .
```

Create a python kernel which will work on this environment. 
```bash
python -m ipykernel install --user --name=arch
```

Launch the jupyter lab and select the python kernel as "arch" 
```bash
jupyter lab
```

To deactivate the virtual environment 
```bash
conda deactivate
```

To remove conda environment
```bash
conda env remove --name arch
```


List all the kernels
```bash
jupyter kernelspec list
```

Uninstall your unwanted kernel
```bash
jupyter kernelspec uninstall arch
```
