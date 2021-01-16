# Using PyATS Genie library on CLI
This repository contains some scripts demonstrating how to use the Genie library to compare the atual operational status of devices with the status when network are considered to be stable.
## Scripts
- `stable.sh` - This script captures a snapshot of the operational status of the device contained in the `testbed.yaml` file and stores in the directory `./output/stable`.
- `modified.sh` - This script captures a snapshot of the operational status of the device contained in the `testbed.yaml` file and stores in the directory `./output/modified`.
- `diff.sh` - This script compares the contents of the `./output/stable` directory with `./output/modified` directory and store the diferences in the `./output/diff` directory.
## How to use this scripts
Clone this repository to your host with this command.
```
git clone https://github.com/fassampaio/genie_cli.git
```
Install the requirements python modules.
```
cd genie_cli
sudo pip install -r requeriments.txt
```
## Links de referências
- [Genie library](https://developer.cisco.com/docs/genie-docs/)
- [Genie models](https://developer.cisco.com/docs/genie-docs/)