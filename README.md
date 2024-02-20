# Thinkpad P52 Hackintosh (MacOS-X Snow Leopard 10.6)
## CMD config files to effectively run MacOS 10.6 on a Thinkpad P52 using virtualbox

# Overview
This repository provides the necessary configuration files and instructions to run MacOS X Snow Leopard 10.6 on a Lenovo ThinkPad P52 using VirtualBox. Snow Leopard on non-Apple hardware can be a challenging endeavor, but with the right setup, it's possible to create a functional virtual environment for testing or development purposes.

# Setup Instructions
Follow these steps to set up Snow Leopard on your ThinkPad P52:

**Install VirtualBox:** If you haven't already, download and install VirtualBox on your system.

**Download Snow Leopard ISO:** Obtain a copy of the Snow Leopard 10.6 installation ISO. You can find this through [archive.org](https://archive.org/details/snow-leopard-install_202112).

**Create VM on VirtualBox:** Follow standard instructions to create a VM. Make sure to allocate sufficient resources (RAM, CPU cores, etc.) for optimal performance. (From trial and error : 1 CPU core and 4-8 gigs of RAM work best)

**Configure VirtualBox:** Use the provided configuration files in cmd in admin mode to modify parameters and mask the CPU. 

**Mount Snow Leopard ISO:** Attach the Snow Leopard ISO to the virtual machine's optical drive in VirtualBox.

**Boot and Install:** Start the virtual machine and follow the on-screen instructions to install Snow Leopard on the virtual disk.

**Post-Installation Setup:** After installation, you may need to install additional drivers or perform tweaks to optimize the virtual environment.

[A comprehensive video tutorial](https://www.youtube.com/watch?v=fhnECybadUw) (you will need to do the cmd config seperately)

# Notes
**Compatibility:** While VirtualBox provides a platform for running Snow Leopard on non-Apple hardware, please note that this setup may not be suitable for production use and is primarily intended for testing and experimentation.
**Legal Considerations:** Ensure compliance with Apple's licensing agreements when installing and using MacOS X on non-Apple hardware.

## Disclaimer
The author of this repository is not responsible for any damages or legal issues arising from the use of this software. Use at your own risk.
