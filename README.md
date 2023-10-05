# TCI-node-red-library
Control your SunSDR radio with TCI for your Expert Electronics radio and make i.e a dashboard

# Requirements
Install the following Palletes:

serial out - https://flows.nodered.org/node/node-red-node-serialport

node-red-dashboard - https://flows.nodered.org/node/node-red-dashboard

ui-level https://flows.nodered.org/node/node-red-contrib-ui-level

rpi gpio https://flows.nodered.org/node/node-red-node-pi-gpio

# Flow description

TRX - Dashboard: Connects to your radio

TCI - Audio: Work in progress

TCI LA3QMA: A collection of almost every TCI 1.9 commands. These can be linked to the TRX Dashboard and/or the TCI set commands flow.

TCI CW: Start point to send CW from your tranceiver.

TCI set commands: Control your tranceiver

StealthLoop I3VHF: Tune your I3VHF

# Usage
I needed to control my radio without Expert Electronics cloud and/or VNC/RDP,

On a public server i can via websocket/mqtt control my radio via TCI and also my tuner.

Please help creating a nice Dashboard to control your SunSDR and update this repository.

Kai Gunter - LA3QMA
