## MEMP for macOS Apple Silicon

## Overview
This script is written using the shell, in order to quickly deploy "LEMP" for AppleSilicon Bigsur, Monterey.

M - MacOS

E - Nginx

M - Mysql

P - PHP

## How to setup
**NOTE**  Require finish setting up command line developer tools before.

1 - Pull source code
- Clone MEMP repository inside `Desktop`
```
cd ~/Desktop
git clone https://github.com/xuandung38/MEMP.git
```
2 - Enter the project folder, give permissions to the install.sh file.
```
cd ~/MEMP
sudo chmod +x install.sh
```

3 - Setup.
```
./install.sh
```
Note: Please enter password or use fingerprint (TouchID) to authenticate when required to be able to install!

Thanks to @ronilaukkarinen for idea

Give me start if this script helpful.
