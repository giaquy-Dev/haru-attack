<div align=center>
 
# HARU DOS
## Methods

```sh
  [Layer 7]
 - cfb     | Bypass CF attack
 - pxcfb   | Bypass CF attack with proxy
 - cfreq   | Bypass CF UAM, CAPTCHA, BFM, etc,, with request
 - cfsoc   | Bypass CF UAM, CAPTCHA, BFM, etc,, with socket
 - pxsky   | Bypass Google Project Shield, Vshield, DDoS Guard Free, CF NoSec With Proxy
 - sky     | Sky method without proxy
 - http2   | HTTP 2.0 Request Attack
 
  [Layer 4]
  -udp     | UDP Attack
  -tcp     | TCP Attack
  
  [Tools]
 - Dns     | Classic DNS Lookup
 - Geoip   | Geo IP Address Lookup
 - Subnet  | Subnet IP Address Lookup
```

## Usage on Linux - Termux
```sh
You must use Python 3.9 or higher

git clone https://github.com/giaquy-Dev/haru-attack.git

Install Python3 modules
 - pip3 install -r requirements.txt  or  pip install -r requirements.txt
Install Chrome (or update it lastest version)
 - wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
 - apt-get install ./google-chrome-stable_current_amd64.deb

OR
 - python3 setup.py

```

## Example
```sh
Use DDoS Panel   : python3 main.py
Use command line : python3 main.py <method> <target> <thread> <time>
      └──────────> python3 main.py cfb https://example.com 100 30
```
