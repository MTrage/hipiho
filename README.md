![PyPI - Python Version](https://img.shields.io/pypi/pyversions/3) ![Tested](https://img.shields.io/badge/Tested%20on-Arch%20Linux%20/%20Manjaro%20/%20Artix%20/%20Ubuntu%20-red)  [![GitHub License](https://img.shields.io/github/license/MTrage/hipiho)](https://github.com/MTrage/hipiho/blob/main/LICENSE)

# HiPiHo
HiPiHi is a Python script that allows to query the state of the Pi-Hole from the terminal, as well as to switch the blocking function on or off.

### Shortened output
![](https://github.com/MTrage/hipiho/blob/main/screenshots/main.png)
### Complete output
![](https://github.com/MTrage/hipiho/blob/main/screenshots/main-all.png)

## Installation
Simply download the script and save it at the desired location °)

### Install with CURL
    su
    curl -fsSL https://raw.githubusercontent.com/MTrage/hipiho/master/usr/bin/hipiho > /usr/bin/hipiho
    chmod +x /usr/bin/hipiho
    exit

### Install with WGET
    su
    wget https://raw.githubusercontent.com/MTrage/hipiho/master/usr/bin/hipiho
    cp hipiho /usr/bin/hipiho
    rm hipiho
    chmod +x /usr/bin/hipiho
    exit

### Install HiPiHo on Debian/Ubuntu with WGET
    wget https://raw.githubusercontent.com/MTrage/hipiho/master/usr/bin/hipiho && sudo cp hipiho /usr/bin/hipiho && rm hipiho && sudo chmod +x /usr/bin/hipiho

### Start / use
The script can of course be called with

    python3 hipiho

Or be made directly executable via

    hipiho 
    
## Help
#### When you start hipiho for the first time, you will be asked for the PI-Hole IP, the port and whether you want the output to be slightly offset or a bit more colourful!

If you make a mistake or the Pi-Hole does not respond to your request, you will be asked again if you want to enter the configuration data again.

If you want to create a new configuration file for the query, you can do this with the option "-n".

If you want to use Borders or IloveCandy, simply enter "yes" in the respective question during setup!

### Borders=no & IloveCandy=no
![](https://github.com/MTrage/hipiho/blob/main/screenshots/ss01.png)
### Borders=no & IloveCandy=yes
![](https://github.com/MTrage/hipiho/blob/main/screenshots/ss02.png)
### Borders=yes & IloveCandy=no
![](https://github.com/MTrage/hipiho/blob/main/screenshots/ss03.png)
### Borders=yes & IloveCandy=yes
![](https://github.com/MTrage/hipiho/blob/main/screenshots/ss04.png)

#### Have fun with it !!!
