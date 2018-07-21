# CasparCG on Windows


This provides a CasparCG server which outputs using NewTek NDI


## Pre-requisites to setup

  * CasparCG server  
    https://github.com/CasparCG/server/releases
  * NewTek NDI AirSend Updater  
    http://pages.newtek.com/NDI-Upgrader-Download-Link.html


## Pre-requisites for use

  * CasparCG client  
    https://casparcg.com/builds/CasparCG%20Client/master/
  * NewTek NDI Tools  
    https://www.newtek.com/ndi/tools/#download-tools


## How to use


```
PS> scanner.exe
PS> casparcg.exe
```

On the same or other machine start `CasparCG Client.exe` and the NDI `Studio Monitor`


## Network ports in use

  * 8000 media server
  * 5250 AMCP
  * 5353 NDI
