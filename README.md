# FAU-conic-optimization-applications
Julia notebooks for the Conic Optimization &amp; Applications course at FAU's Departments of Mathematics and Data Science.

**Important**: This code is simply meant to illustrate some concepts discussed during the course. It is provided "as is" without any guarantee of correctness or of efficiency, so use it at your own risk!


## Installation
To run these jupyter notebooks you will need to:

### (1) Install Jupyter Notebook
Follow the [Jupyter Notebook installation instructions](https://jupyter.org/install).

### (2) Install Julia
[Download Julia](https://julialang.org/downloads/) and install it. On Linux: unpack the archive and make sure you can run the executable file `julia` that you will find inside the `bin/` folder. You may want to make sure that the executable file is in your system path. If so, you should be able to start a Julia session from the command line simply by running the command
```
$ julia
```

(press `Enter` after typing this command)

### (3) Installing the IJulia package
Once you have a working installation of both Jupyter Notebook and Julia, you need to install the Julia package IJulia. For this, start a Julia session and then run the following commands:
```
>> using Pkg
>> Pkg.add("IJulia")
```
Wait until the package installation is complete. You can close the Julia session.

### (4) Initialize this repository
Clone this repository to your computer, navigate to it in a terminal window, and start a Julia session from within it. Then, run
```
>> using Pkg
>> Pkg.activate(".")
>> Pkg.instantiate()
```
This may take a while, so please be patient. Once the installation is complete, you can close the Julia session.

### (5) Run the Julia notebooks
You should now be ready to run the Julia notebooks in this repository. To do this, open a terminal window, navigate to the folder with the notebooks, and run
```
$ jupyter-notebook <name-of-the-notebook>
```
You should of course substitute `<name-of-the-notebook>` with the actual name of the notebook you want to run! The notebook should open in your browser.
