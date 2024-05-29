# 5G Roaming using Open5GS (testing with PacketRusher)
## Documentation: https://medium.com/@vidime.sa.buduci.rok/5g-roaming-open5gs-packet-rusher-dacb34f3497c
## Troubleshooting: https://medium.com/@vidime.sa.buduci.rok/5g-roaming-troubleshooting-open5gs-packetrusher-ueransim-dcaa6740eb94
## Repository structure:
### Core1 and Core2 are two 5G Core network with different PLMN code. Both have configurations for running them on Ubuntu 20.04 (Kernel 5.15) and configurations of PacketRusher to test each other's Roaming features
### /open5gs/ contains configurations for the Core system (including changed mme.yaml from Open5GS Quickstart which is redundant, not used in the project)
### /systemd/ contains confugirations for running the daemons with systemctl
### config.yml is configuration file for PacketRusher
