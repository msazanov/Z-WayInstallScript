# Z-Way Install Script

This repository contains a convenient installation script for Z-Way, a popular Z-Wave home automation software. The script is designed to work with Raspbian/Debian and Ubuntu distributions.

## Prerequisites

- A compatible Linux distribution (Raspbian Buster, Raspbian Bullseye, or Ubuntu 20.04 and higher)
- A supported architecture (armhf, aarch64, or x86_64)
- Internet access for downloading packages and updates

## Installation

To install Z-Way using the provided script, run the following command in your terminal:

```bash
wget -qO - https://raw.githubusercontent.com/msazanov/Z-WayInstallScript/main/RaspbianInstall | sudo bash
```

The script will automatically detect your Linux distribution and architecture and then proceed with the installation.

## What the script does

1. Removes any old Z-Wave repository configuration
2. Installs required dependencies
3. Detects the Linux distribution and version
4. Checks for compatibility with the supported distributions and architectures
5. Sets architecture-specific variables and installs additional packages based on the architecture
6. Adds the Z-Wave.Me repository and updates the package list
7. Installs or reinstalls the necessary Z-Way packages
8. If configuration files have been modified, prompts the user to restore them to their default state

## Support

If you encounter any issues or have questions, please contact Z-Wave.Me support for more information.
