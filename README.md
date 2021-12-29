# galactic_quenching

This is Nicholas Owens' Phys 437 A scripts for the University of Waterloo.
The project was completed in the Fall of 2021 under the supervision of Professor Michael Balogh.

To run the notebook provided, the Python FSPS library must be installed and prepped. Refer to "https://dfm.io/python-fsps/current/" to learn more about FSPS for python. This includes installation guidelines and more.
Ready the FSPS library before opening python by typing the following into the terminal:

export SPS_HOME="/home/nialow/Documents/python_pkgs/"

Test to ensure you have access to FSPS:

python -c "import fsps"

This should only return an error if the environment has not been readied. 

FSPS is optimized to run on Linux systems. Likely, the notebook will not work on Windows or MacOS. As such, Linux should be run either virtually or as the primary operating system when using this program.

A portion of this program draws data from the GOGREEN survey and requires access to datalab. To ensure that the most recent version of Data Lab is installed, type the following  into the terminal:

python -m pip install --upgrade noaodatalab

Following this, test to ensure that you have access to gogreen.

python -c "from dl import queryClient as qc, storeClient as sc; print(sc.services('gogreen_dr1'))"

In addition, ensure that NumPy, DateTime, and MatplotLib are all installed on your machine.
