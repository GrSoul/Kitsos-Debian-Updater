# Kitsos Debian Updater

This is a very simple bash script to update your Debian-based computer (Ubuntu, Raspbian, etc.)

Runinng it your system will update all packages (including snap and flatpak) and clean up the ones that are not needed anymore.

## Installation

Download the file named "update". Open a terminal in the same folder and type:

```
sudo -s
mv update /usr/bin/
chmod +x /usr/bin/update
```

## Usage

Just open a terminal and type 

```
update
```
