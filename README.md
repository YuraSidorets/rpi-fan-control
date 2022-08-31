# rpi-fan-control
Manual for Raspberry PI fan installation 

# Circuit
![Circuit](/raspberry-pi-fan-controller-schematic.png)

# Requirements:
- If pip is not already installed run:
`sudo apt install python3-pip`

- Install requirements globally
`sudo pip3 install -r requirements.txt`

# Install script
- `./script/install`

# Own modifications
ON_THRESHOLD = 65

OFF_THRESHOLD = 55

SLEEP_INTERVAL = 5

GPIO_PIN = 17
