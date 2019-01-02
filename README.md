# MagicMirror 2.6.0 Installer for the Pi Zero

This installer allows users of the Raspberry Pi Zero to also access the popular MagicMirror personal assistant project which was voted number 1 Pi project by MagPi in 2016.

## Installation

### Raspberry Pi

Install the most recent available Raspbian Image (This is tested on Raspbian Jessie and Raspbian Stretch). You do not need the 'recommended software', but you do need the 'desktop'. Therefore do not use the 'Lite' version.

Set up your Internet connection. You may also want to set up SSH and VNC at this time.

### Magic Mirror Installation

Clone this project into your home directory (It should come down into the folder ~/MagicMirrorPi0Installer)

```
git clone https://github.com/ac2799/MagicMirrorPi0Installer
```

Run the command

```
sudo chmod a+x ~/MagicMirrorPi0Installer/RaspberryPi0.sh && sh ~/MagicMirrorPi0Installer/RaspberryPi0.sh
```

This will make the shell script executable, and if that is successful, it will also run the script.

This can take up to an hour, depending on how many updates and upgrades need to be made to your Raspbian version. There is minimal interaction required, except to press enter a couple of times to agree to updates outside of the repository (e.g. updates to the raspbian operating system).

### Further details

The main repository for the Magic Mirror is at https://github.com/MichMich/MagicMirror. All the work was done by them, this is just to hold the Pi Zero script until such time as it can be brought into the main project.

\- Andrew Chu
