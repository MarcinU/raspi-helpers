# raspi-helpers
## Scripts to assist some tasks on the Raspberry Pi 2.

### scripts/jasper-installer.sh
##### Script to assist installing Jasper on Raspbian Lite
##### Tested on a fresh install of Jessie Raspbian Lite
##### Expand for raspbian to use entire disk with

##### Upon reboot you could clone the repository or just download the script
##### Below is if you want to download the script

`wget https://raw.githubusercontent.com/unixabg/raspi-helpers/master/scripts/jasper-installer.sh`

`chmod +x jasper-installer.sh`

##### Install screen - as the script takes a loooooong time to finish

`sudo apt-get screen`

Start scree

`screen`

##### Run the script

`~/jasper-installer.sh`

You can reattach the session using:

`screen -r`

##### Force audio to headphone jack ref: https://www.raspberrypi.org/forums/viewtopic.php?f=91&t=40872

`sudo amixer cset numid=3 1`

FIXME

