# mct
MassOS Container Tool

## What is MassOS Container Tool?
MassOS Container Tool is a simple Bash program to creating, removing and running Linux containers in MassOS Operating System. Almost all major Linux distribution is supported and the tool is only based on Systemd.

## Installation
```
wget https://raw.githubusercontent.com/ClickNinYT/mct/main/mct
chmod +x mct
sudo cp mct /usr/bin
rm mct
```
After that, run `sudo mct about` to confirm that MCT is installed!

## Usage
All commands and function can be found by running `sudo mct help`. A list of available Linux distribution for creating a container can be found by running `sudo mct avail`. For example, if you want to create a Ubuntu container, run `sudo mct create` and enter in `ubuntu`. Simple.
