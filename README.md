# LTSBscan

Uses nmap's OS fingerprinting to figure out which PCs are running Windows and returns the most probable version.

## INSTALLATION and USE (this assumes anaconda is already installed)
* Install nmap
> (apt) sudo apt-get install nmap

> (yum) sudo yum install nmap

* Import the conda environment
> conda env create -f LTSBscan.yml

* Scan must be run with elevated credentials. The following commands should work.
> sudo -s

> export PATH="$HOME/anaconda/bin:$PATH"

> source activate LTSBscan

> python LTSBscan.py
