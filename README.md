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
Using MCT is fairy simple, you can get a list of available commands using `sudo mct help`, or get a list of available Distribution using `sudo mct avail`. For example, if you want to create a container named "MyContainer" with Ubuntu, just run `sudo mct create ubuntu MyContainer` and wait patiently. After that, everytime you want to boot the container up, just use `sudo mct launch MyContainer`.

## What is supported?
Currently, MCT is fully supported. However, GUI Apps will not working for now. If you want to run GUI Apps, refer to Arch Wiki for more information. [Arch Wiki - X11 Forwarding](https://wiki.archlinux.org/title/systemd-nspawn#Use_an_X_environment)

