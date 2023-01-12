
# GLPI_install_script

## About this script

This script was written in order to quickly install the latest version of GLPI (currently 10.0.05) on Ubuntu & Debian servers.

The script will install, Apache, MariaDB, PHP and dependencies, the latest version from the [Official GLPI repo](https://github.com/glpi-project/glpi) and configure the database for you.
Once the script is executed, the only thing you have to do will be to connect to GLPI.

### Default accounts
| Login | Password | Role |
|--|--|--|
glpi|glpi|admin account
tech|tech|technical account
normal|normal|"normal" account
post-only|postonly|post-only account

### Read the documentation
Know that I have no connection with the team that develops GLPI and/or TecLib.
If you encounter a problem with this script on one of the compatible distributions, you can create an issue, i will help you with pleasure.
If you encounter a problem with GLPI and/or need more information on how it works, I recommend that you read the documentations:

[GLPI Administrators Docs](https://glpi-install.readthedocs.io/)

[GLPI Users Docs](https://glpi-user-documentation.readthedocs.io/)

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
