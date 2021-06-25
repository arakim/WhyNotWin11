# WhyNotWin11
Detection Script to help identify the more niche settings for why your PC isn't Windows 11 ready

----

## A Comptiable PC
Field|Windows 11 Compatible Value|Description
----|----|----
TPM|Present|On-board security chip
BOOT|UEFI or Secure|OS boot method, configurable on UEFI settings
DISK|GPT|Next Generation Disk Layout

## To-Do

- [ ] Hard Floor Checks:
    - [ ] Cores >= 2
    - [ ] CPU Freq >= 1 GHZ
    - [ ] RAM >= 4 GB
    - [ ] Storage >= 64 GB
    - [ ] TPM >= 1.2
    - [x] SecureBoot
    - [ ] ~~SMode~~ (WhyNotWin11 is not compatible with S Mode Devices)
- [ ] Soft Floor Checks:
    - [x] TPM >= 2.0
    - [ ] CPU Compatibility list
- [ ] A fancier GUI

## How to build from source code

1. Download and run "AutoIt Full Installation" from [official website](https://www.autoitscript.com/site/autoit/downloads). 
1. Get the source code either by [downloading zip](https://github.com/rcmaehl/WhyNotWin11/archive/master.zip) or do `git clone https://github.com/rcmaehl/WhyNotWin11`.
1. Right click on `WhyNotWin11.au3` in the WhyNotWin11 directory and select "Compile Script (x64) (or x86 if you have 32 bit Windows install).
1. This will create WhyNotWin11.exe in the same directory.

This program is free and open source. Feel free to download and modify. Please do not sell exact copies.