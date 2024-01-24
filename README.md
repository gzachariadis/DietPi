
## DietPi

DietPi is an extremely lightweight and slim/diet version of Raspberry OS, it's not it's own Operating System or Distribution. DietPi is just a bundle of scripts on top of a standard Debian installation. 

Depending on your Single Board computer (SBC), DietPi is using different base images. Mainly used images are Armbian, Meveric or for PRi boards Raspberry OS, that means that Raspberry OS is used as base image, including kernel or firmware.

## Why DietPi instead of Raspian?

- Reduced amount of installed software.
- DietPi boots much faster. 
- The mount of r/w operation has been reduced down to a minimum to allow a longer lifetime of SD cards.
- DietPi uses a highly optimized kernel and File System, less prone to errors.
  
Advantages :

- SSH Pre-Installed ✅
- Lightspeed Boot ✅
- Logs in RAM [Default] ✅
- Temporary files in RAM [Default] ✅
- Low RAM & Disk Usage ✅
- Low Power Consumption ✅
- Headless Mode [Default] ✅
- DietPi-Launcher  - Easy Install/Unistall lots of apps (including Pihole, Unbound) ✅
- Firewall pre-installed?
- Well-Documented ✅
- Malware scanner?

Disadvantages :

- Installing apps, runs them locally. ❌
- Docker can be set up and used, but requires manual configuration. ❌ 

##  Apline Linux 

Sure i could use just pure Debian or Alpine, but why? I would need to add my typical required tools to them anyway, like log2ram, ntp sync, docker, micro, dig, etc. Just not worth my time to do that manually when DietPi already has most of those included without being bloated.

alpine linux (as an OS) does wonder on raspberry pi. if you only need docker (or podman) that can be a good choice. it has obscure functions, and works a bit differently than other common distribution but it does wonders for performance, mostly because the bare install is less than 20m, and it load and runs on ram

## Raspian 



## Comparative Data

- https://docs.google.com/spreadsheets/d/1mDHGZC-H6tU6_O8kuLTG8d4A8Nt7lV1Q7MXTR_6qw30/edit#gid=0

