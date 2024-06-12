# idracUbuntu24.04
Dell iDrac Install Script for Ubuntu 24.04

# Disclaimer
This is a fork of the edits to Dell's outdated iDRAC installer.

This script is a modified version of the script provided by Dell. It is not endorsed by Dell!

@Dell - Please dont sue me for Modifying this script 


# Usage

1. Download the official tar for the iDrac Service module from dells webiste. This script has been tested and confirmed working with version `OM-iSM-Dell-Web-LX-350-1862_A00`

2. Extract the tar and replace the setup.sh script with the one from this repository

3. give the script execution permissions using `chmod +X` 

4. run - `sudo bash setup.sh`


# Changes 

Two changes have been made to this script

1. Changed the `$VERSION_ID` variable to `$VERSION` to match the changes to the `os-release` file that comes on UBUNTU 20.04
Change is on line 391

2. Changed the check to be `24` instead of `18` change is on line 399
