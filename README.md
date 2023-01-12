# GLPI_install_script  

## About this script  

This script was written in order to quickly install the latest version of GLPI (currently 10.0.05).  

The script will install, Apache, MariaDB, retrieve from the [GLPI repo](https://github.com/glpi-project/glpi) the l>  
All you have to do is connect to GLPI.

## Compatibility
Since this script uses apt, it currently only works on debian-based distributions.
This script was tested on this distributions:
| OS | VERSION| COMPATIBILITY|
|--|--|--|
|Debian|10|⚠️ Never tried, if you choose to force the script, it is at your own risk. |
|Debian|11|✅|
|Ubuntu|22.04|✅|
|Ubuntu|22.10|⚠️ Never tried, if you choose to force the script, it is at your own risk.|


## How to use
GLPI_install_script  is installed by running one of the following commands in your terminal. You can install this via the command-line with either curl or wget.

    wget https://raw.githubusercontent.com/jr0w3/GLPI_install_script/main/glpi-install.sh && bash glpi-install.sh
or with curl 

    curl -O https://raw.githubusercontent.com/jr0w3/GLPI_install_script/main/glpi-install.sh && bash glpi-install.sh
