# Experiment 01: Install Ubuntu Linux Using Oracle VirtualBox

## Aim

To install Oracle VirtualBox, create a virtual machine, and install Ubuntu Linux on that virtual machine.

## Requirements

- A Windows, macOS, or Linux computer supported by Oracle VirtualBox.
- Internet connection.
- Sufficient free disk space for the Ubuntu ISO and virtual machine.
- Oracle VirtualBox installer.
- Ubuntu Desktop ISO image.

## Official Downloads

- [Oracle VirtualBox Downloads](https://www.virtualbox.org/wiki/Downloads)
- [Ubuntu Desktop Download](https://ubuntu.com/download/desktop)
- [Oracle VirtualBox User Manual](https://www.virtualbox.org/manual/)

Use the Ubuntu Desktop ISO that matches your computer's processor architecture. The settings below are suggested starting values; adjust them to suit your host computer and the Ubuntu version you download.

## Procedure

1. Download Oracle VirtualBox from the official website.
2. Run the installer and follow the installation wizard.
3. Download the Ubuntu Desktop ISO image from the official Ubuntu website.
4. Open Oracle VirtualBox and select **New**.
5. Enter a name such as `Ubuntu-Linux` and select the downloaded Ubuntu ISO when prompted.
6. Choose the appropriate operating-system type and version if VirtualBox does not detect them automatically.
7. Allocate memory and CPU resources without assigning so much that the host operating system becomes unresponsive. A reasonable starting point for many systems is 4 GB RAM and 2 virtual CPUs, if available.
8. Create a virtual hard disk. A dynamically allocated disk of around 25–30 GB or more is a practical starting point for a desktop installation.
9. Review the configuration and create the virtual machine.
10. Start the virtual machine. Follow the Ubuntu installer prompts to select language, keyboard layout, network settings, and installation options.
11. Complete the installation and restart the virtual machine when prompted.
12. If the installer asks you to remove installation media, eject/detach the ISO from the virtual optical drive before continuing.
13. Log in to Ubuntu and verify that the desktop loads successfully.
14. Capture screenshots of the relevant steps and add them to the `screenshots/` folder.

> **Important:** During installation, select the virtual machine's virtual disk, not your computer's physical disk. Do not change partitions on the host computer for this experiment.

## Suggested Screenshots

Save your own screenshots in the `screenshots/` directory. Suggested filenames:

1. `01-virtualbox-installed.png`
2. `02-create-virtual-machine.png`
3. `03-vm-settings.png`
4. `04-ubuntu-installer.png`
5. `05-ubuntu-desktop.png`

Update the list above if you use different filenames. Do not add screenshots you did not capture yourself.

## Result

**Result to fill in after completing the experiment:** Oracle VirtualBox was installed, a virtual machine was created, and Ubuntu Linux was installed and launched successfully.

## Learning Outcome

- Understood the purpose of virtualization.
- Learned how to create and configure a virtual machine.
- Learned how to install a Linux operating system in a virtual environment.
- Practised documenting a laboratory experiment with screenshots.
