# mct
```
 __  __                ____   _____    _____            _        _                   _______          _ 
|  \/  |              / __ \ / ____|  / ____|          | |      (_)                 |__   __|        | |
| \  / | __ _ ___ ___| |  | | (___   | |     ___  _ __ | |_ __ _ _ _ __   ___ _ __     | | ___   ___ | |
| |\/| |/ _` / __/ __| |  | |\___ \  | |    / _ \| '_ \| __/ _` | | '_ \ / _ \ '__|    | |/ _ \ / _ \| |
| |  | | (_| \__ \__ \ |__| |____) | | |___| (_) | | | | || (_| | | | | |  __/ |       | | (_) | (_) | |
|_|  |_|\__,_|___/___/\____/|_____/   \_____\___/|_| |_|\__\__,_|_|_| |_|\___|_|       |_|\___/ \___/|_|
    
```

## What is MassOS Container Tool?
MassOS Container Tool is a simple Bash program to creating, removing and running Linux containers in MassOS Operating System. Almost all major Linux distribution is supported. MCT is heavily based on Systemd-Nspawn which is used to spawn a lightweight container namespace.

## Installation
```
wget https://raw.githubusercontent.com/ClickNinYT/mct/main/mct
chmod +x mct
sudo cp mct /usr/bin
rm mct
```
Should install the latest version of MCT!\
After that, run `sudo mct about` to confirm that MCT is installed!

## Usage
Using MCT is fairy simple, you can get a list of available commands using `sudo mct help`, or get a list of available Distribution using `sudo mct avail`. For example, if you want to create a container named "MyContainer" with Ubuntu, just run `sudo mct create ubuntu MyContainer` and wait patiently. After that, everytime you want to boot the container up, just use `sudo mct launch MyContainer`.

## What is supported?
Currently, MCT is fully supported. However, GUI Apps will not working for now. If you want to run GUI Apps, refer to Arch Wiki for more information. [Arch Wiki - X11 Forwarding](https://wiki.archlinux.org/title/systemd-nspawn#Use_an_X_environment)
Audio and GPU Accerelator is currently not officially supported by MCT.

## About NG Project
NG Is a new upcoming branch of MCT, using LXC as the base system to manage containers. The benefits you get is more distribution will be supported. GPU Accerelator, Audio and proper GUI (or a Full Desktop Environment) will be supported.

