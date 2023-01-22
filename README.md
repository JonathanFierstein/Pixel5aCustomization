# Pixel 5a Customization

#### How to root your Pixel 5a, Install a custom recovery if you prefer, and install a custom version of Android (Like Lineage for example), and complete some basic tuning of the OS, once installed.

Information and data collected by Jonathan Fierstein



## Introduction

When I purchased my Pixel 5a a year ago, I created this repository to track what I did to root the phone and get a custom recovery installed and then to install Lineage or whatever I ended up deciding to put on it.   Unfortunately, I was so excited hacking my new phone that I completely forgot to take notes on the process.  By the time I was finished, I wasn’t 100% sure which steps I took at part of the process and I didn’t want to put a procedure here and then make a mistake and give everyone a procedure for how to brick their phone.   Well, after just over a year, I cracked my screen and ordered a replacement from assurance.   This time, I will take very careful notes.    Better late than never :)



## Prerequisites

##### Unlock the Pixel 5a Bootloader

This command unlocks the phone so we can flash firmware to it.   Unfortunately, unlocking the bootloader requires the memory on the phone to be wiped.   This seems totally stupid at first, but, it prevents someone from stealing a phone, then unlocking the bootloader so they can install tools which allow them to steal all the secrets the phone has.   



This is why, after you tweak your Pixel 5a into a configuration you are happy with, you really should lock your bootloader so if you lose the phone your data is as safe as it would normally be.



To unlock the bootloader you need to connect the Pixel 5a to a Windows desktop.   If you hold the windows key and press R, the run dialog will pop up.  In the run box, type CMD and press enter.   Then you type the commands shown below:



```
C:\AndroidSDK\adb.exe devices

C:\AndroidSDK\adb.exe reboot bootloader
```

