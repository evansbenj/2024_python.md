# Install python modules
```
python -m pip install MODULENAME
```

# Add module to spyder

As detailed here: https://docs.spyder-ide.org/5/faq.html#using-packages-installer
```
conda create -n my-env -c conda-forge spyder-kernels MODULENAME
```
```
pip install spyder-kernels==2.5.*
```
