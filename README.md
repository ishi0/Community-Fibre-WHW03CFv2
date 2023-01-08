# Community-Fibre-WHW03CFv2

This repo has been made for people like me who wanted to flash retail Linksys firmware on the Community Fibre Linksys Velop WHW03CFv2 router. If you have stumbled across this repo then you most likely are aware that the firmware provided by Community Fibre does not allow retail firmware to be flashed on to it. This repo is your soloution.

Programs needed:
PuTTY. PuTTY is a free and open-source terminal emulator, serial console and network file transfer application. We need this program so that once we flash OpenWRT onto the router we can SSH into it. By being able to SSH into the router we are able to copy over the retail firmware temporarily to the internal storage. It will also allow for the important process of erasing the Community Fibre firmware partitions and writing the retail firmware onto the just erased partitions. 
WinSCP. WinSCP is a program crucial as it allows us to transfer the retail Linksys image onto the router when running OpenWRT

Files needed:
OpenWRT firmware. The OpenWRT firmware which is in this repository is a working build of OpenWRT. For this project we are going to use the OpenWRT firmware so that we can SSH into the router. This build of OpenWRT works and can be substituted for the retail firmware if any more advanced users would like to use it over the retail Linksys firmware.

Installation steps:
The installation procedure can be found in the Wiki of this repo.
