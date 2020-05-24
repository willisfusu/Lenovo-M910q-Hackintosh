# Lenovo M910q Hackintosh EFI

This EFI folder is used for Lenovo M910q to install hackintosh via Opencore. 

## Computer Spec

CPU: i5-7600T

iGPU: intel HD graphics 630

Disk01: Samsung SSD 860 EVO 500G

Disk02: Samsung MZVLM128HEGR-000L1

Chipset: Q270

RAM: 16GB

## What works

* Audio speaker
* Audio jack connector
* USB ports: custom made in USBPorts.kext
* Display (only DP, because I don't have a HDMI display. if you want to use the HDMI, you need patch by yourself.)

## What does not work

* sleep and wake: can not wake up from a long time sleep. error is Darkwake Exit Failure

## How to use

* read the [Vanilla guide](https://dortania.github.io/OpenCore-Desktop-Guide/ ) first
* use my EFI to replace your EFI folder

