# RemoteChess
This is a project to allow 2 players to enjoy chess from a distance. Through sensors, robotics, and embedded systems, the physical chess pieces can move remotely.

# Running
Check you are on 'empire_5G' wifi. Run 'ssh pi' (ssh alias) to logon. Use AngryIPScanner to check the raspberrypi hostname is correct.

# Install

## Circuit Python
`pip3 install adafruit-circuitpython-lis3dh` -- circuit python
`sudo pip3 install adafruit-circuitpython-mpr121` -- capacitive touch sensor

## Blinka
`sudo pip3 install --upgrade adafruit-python-shell`
`wget https://raw.githubusercontent.com/adafruit/Raspberry-Pi-Installer-Scripts/master/raspi-blinka.py`
`sudo python3 raspi-blinka.py`
`ls /dev/i2c* /dev/spi*` -prints-> `/dev/i2c-1 /dev/spidev0.0 /dev/spidev0.1` -- confirm proper install

# API Documentation
## Touch Capacitor
https://circuitpython.readthedocs.io/projects/mpr121/en/latest/index.html
