
# Screen Off

A useful script for home server users who like me are using laptops as their home servers. This script allows you to turn your laptop screen off (default 2 mins) since there is no such functionality available natively.

## Installation

1. Clone the repository:

       git clone https://github.com/hrshith/Screen-Off.git 

## Usage

This section would explain how to use the script or utility to turn off the laptop screen. It might include command-line.


###  Run the script 

Run the following command to turn off the laptop screen:

    ./screenoff.sh

###  Issues 

Run the following command to allowing the permission 

    chomd +x screenoff.sh


If you get the below error, you are running the command via SSH, this script works only if you run it on the device.

    setterm: terminal xterm-256color does not support --blank





 
