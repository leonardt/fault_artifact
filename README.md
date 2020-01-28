Full documentation can be found in the `~/cav_artifact/README.md` directory.

# VM
* VirtualBox 6.0
* Ubuntu (64-bit)
* 4096 MB RAM
* 10 GB Virtual Hard Disk (VDI, Dynamically allocated)
* Installation Media: ubuntu-18.04.3-desktop-amd64.iso
* User Name: fault
* Password: fault

# Host
* macOS Catalina 10.15.2
* MacBook Pro (13-inch, 2017, Four Thunderbolt 3 Ports)
* 3.5 GHz Dual-Core Intel Core i7
* 16 GB 2133 MHz LPDDR3

# Env
apt packages
* git
* make
* gcc
* g++
* g++-7
* libgmp-dev
* libmpfr-dev
* libmpc-dev
* verilator
* iverilog
* ngspice

```
wget http://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh
```

pip packages
* pytest
* mantle
* fault

```
pysmt-install --msat --confirm-agreement
pysmt-install --z3 --confirm-agreement
export PYTHONPATH="/home/fault/.local/lib/python3.7/site-packages:${PYTHONPATH}"
git clone https://github.com/leonardt/fault.git
```
