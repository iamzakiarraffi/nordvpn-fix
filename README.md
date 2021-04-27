    #nordvpn-bin#    
(CLI app) 3.88 has an issue where it throws up a “Whoops! Cannot reach System Daemon” error. NordVPN works fine in Network Manager with OpenVPN. 
Fix is as follows:
You need to create the system group manually and add yourself to that group:
