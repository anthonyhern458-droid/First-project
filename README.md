# First-project

Raspberry Pi 4 Homemade Gameboy

##Overview

Hello and welcome! I have decided to start on my own little project to familiarize myself with how important computational software is to hardware. I have always wanted to be a computer hardware engineer since working hands on with computers has always been more interesting to me and I have decided to go one step forward. 

##Materials

Raspberry Pi 4 (4GB RAM)
MicroSD Card (64GB)
USB-C Power Supply
Micro HDMI to HDMI Cable
Enclosure

##Software

Batocera (Retro Gaming OS Emulator) https://batocera.org/download
balenaEtcher (To flash the OS onto the SD card) https://etcher.balena.io/

##Goal

To build a handheld retro gaming console and learn about coding and emulation through Batocera.

##Inspiration

My inspiration for this idea came from talking to my friends, asking ChatGPT questions about the project and YouTube. This project stems from my personal appreciation of computer engineering and all of its fun quirks. 

##Progress Log

October 30th, 2025

For today, the main thing I want to get started on is downloading Batocera onto the Raspberry Pi. Batocera is an emulation operating system software that can be flashed onto any device to make it an emulator for retro games, such as SNES, NES, Nintendo 64, Sega Genesis, Playstation 1 and 2, and even more modern consoles such as the Wii, Xbox 360 and Nintendo Switch. For the purpose of this project, I will be sticking to the retro console games. 

To start things off, I will download Batocera and balenaEtcher onto my computer.
Once they are both downloaded, I launch balenaEtcher on my computer and connect the SD card to my computer.
On balenaEtcher, I click "download from file" and click the Batocera image. Then, I choose the destination I would like to flash it to, which is the SD card, and once I start flashing it onto there I wait for it to finish to see if it worked.
While that is flashing, I am going to download one game for each console: SNES, NES, Nintendo 64, Sega Genesis, and Playstation 1. Once I have the games downloaded, I will sort them into a folder called "Games" and organize them in there.

Once Batocera has been successfully flashed onto the SD card, I go ahead and remove the SD card from my computer and connect it to the Raspberry Pi. I also connect the USB-C power supply and the HDMI cable. I make sure it boots up and, voila! The Raspberry Pi has been successfuly flashed with Batocera!

##Issues

In attempt to connect my controller to the Raspberry Pi on the Batocera menu, the controller did not work. The cable I used for the controller was a charging only cable, not a data cable. I ended up connecting my keyboard to the Raspberry Pi and navigating the menu to connect my controller via bluetooth to the Raspberry Pi and I made it work with little to no latency lag. 

##Next Steps

Begin designing LEGO handheld case
Research what display, battery, and speaker I can use to make the handheld portable. 
Download more games and play around with the Raspberry Pi

##Sources

AI (ChatGPT)
https://www.youtube.com/watch?v=5Jr-0UjgC8I (The guide that inspired me)
https://www.romsgames.net/ (Where I was able to download all my sources)
https://batocera.org/download
https://etcher.balena.io/#download-etcher
