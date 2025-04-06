# fedora-setup
  
An automated post-install script to set-up Fedora 41 for my personal use.

#### Installation

This script is supposed to be run right after a fresh install.

You can download the script from the repo or use this one-liner command, there are no dependencies required.

`sudo bash -e -c "$(wget -qO- https://raw.githubusercontent.com/ramosfabiano/fedora-setup/main/fedora-setup.sh) | tee log.txt"`

After the install, reboot.  *Note that this script is NOT idempotent.*