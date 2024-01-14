# Envy Boot for Ubuntu Server

## Getting Started

### Prerequisites

Note: Installing Ubuntu Server 22.04 required an internet connection 

### Ubuntu Installation
* Install Bbuntu Server 22.04 
* Choose full install when prompted
* Use the following settings:
````
name: envy
hostname: envy
user: envy
password: envy
confirm password: envy
````
* Install openssh server when prompted
### Envy Installation
* Type the following into the CLI:
````
git clone https://github.com/notkirb/envy-ubuntu
cd envy-ubuntu
sudo sh setup.sh
````
* If everything went without errors, your PC will now restart and boot directly into Envy 7 beta 2!
## Authors

* **WLABESAMIS** - (https://github.com/wlabesamis)
* **notkirb_** - (https://github.com/notkirb)
## Acknowledgments

* Thank you to THEPCSPY
* **THEPCSPY** - (https://thepcspy.com/read/building-a-kiosk-computer-ubuntu-1404-chrome/)
