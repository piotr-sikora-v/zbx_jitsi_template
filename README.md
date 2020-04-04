# Zabbix Jitsi-meet template

Ver 0.1

Tested on zabbix 4.2

## Features:
  - fetch all data from videobridge
  
## Macros:
  - {$JITSI_COLIBRI_URL} defailt to: http://localhost:8080/colibri/stats
   
## Install:
Just import template

## Setup:
In /etc/jitsi/videobridge/config set line:
```
JVB_OPTS="--apis=rest"
```

## Changelog:
### 0.1
 - Fetch all data from videobridge
