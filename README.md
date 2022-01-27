# Linux Nvidia Drivers

This repository stores the steps to install official nvidia drivers for Ubuntu OS.

## Getting Started

```bash
# Add repository
sudo add-apt-repository ppa:graphics-drivers/ppa
sudo apt update

# Identify your graphic card model and recommended driver
ubuntu-drivers devices

# Auto install
sudo ubuntu-drivers autoinstall

# Alternative, you can install the drivers you want
sudo apt install nvidia-470
```

## Reference
[link](https://linuxconfig.org/how-to-install-the-nvidia-drivers-on-ubuntu-18-04-bionic-beaver-linux)
