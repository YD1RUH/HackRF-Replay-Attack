# HackRF-Replay-Attack
replay attack using HackRF with GUI. Attack start with record the signal saved as complex file then transmit the complex file result from recording process with HackRF.

![image](https://github.com/YD1RUH/HackRF-Replay-Attack/blob/main/screen.jpg)

## Requirement
- Linux Operating System 
- python3 : `sudo apt install python3`
- xterm : `sudo apt install xterm`
- DearPyGUI : `pip3 install dearpygui`
- HackRF library : `sudo apt-get install hackrf libhackrf-dev`
- GNURadio3.10 : [Installation guide](https://wiki.gnuradio.org/index.php/LinuxInstall)
- SoapySDR : [Installation guide](https://github.com/pothosware/SoapySDR/wiki/BuildGuide#get-the-source-code)
- SoapySDR HackRF : [Installation guide](https://github.com/pothosware/SoapyHackRF/wiki#building-soapy-hack-rf)

## How To Use
- clone the source using `git clone https://github.com/YD1RUH/HackRF-Replay-Attack.git`
- go into the directory `cd HackRF-Replay-Attack`
- make all file executable `chmod +x *`
- Open terminal, then run `./hackrf-replay`
