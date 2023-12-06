### For related instructions and points of attention, please see [warp series video description](https://www.youtube.com/playlist?list=PLMgly2AulGG-WqPXPkHlqWVSfQ3XjHNw8) [Update log](https://ygkkk.blogspot.com/ 2022/09/cfwarp-script.html)

### 1. WARP is a multi-functional one-click script that supports direct installation of pure IPV4 and pure IPV6 VPS, and is supported by mainstream Linux systems.
```
bash <(wget -qO- https://gitlab.com/rwkgyg/CFwarp/raw/main/CFwarp.sh 2> /dev/null)
```
or
```
bash <(curl -Ls https://gitlab.com/rwkgyg/CFwarp/raw/main/CFwarp.sh)
```

Note: For a VPS that has installed warp, if other scripts fail to run and download, and the script interface cannot be entered, please try the following shortcut to terminate the warp.

  1. Terminate warp-go:
  ```kill -15 $(pgrep warp-go)```

  2. Terminate wgcf:
  ```systemctl stop wg-quick@wgcf```


-------------------------------------------------- -------------------

### 2. Multi-platform optimization of WARP peer IP + unlimited generation of WARP-Wireguard configurations. One-click script, recommended for use by Apple phones and Android phones on the local network
```
curl -sSL https://gitlab.com/rwkgyg/CFwarp/raw/main/point/endip.sh -o endip.sh && chmod +x endip.sh && ./endip.sh
```

The Replit platform generates unlimited WARP-Wireguard configurations with one click: https://replit.com/@ygkkkk/WARP-Wireguard-Register

Replit platform generates unlimited WARP+ keys with one click (more than 20 million GB traffic): https://replit.com/@ygkkkk/WarpKey-Register-PRO

-------------------------------------------------- ----------
### 3. Windows platform warp official client prefers peer IP application

Note: By default, it can only be operated on C drive or desktop.

Instructions for use: Unzip the downloaded (WIN side warp optional IP-v23.11.15.zip) file, refer to the usage instructions and video tutorials

-------------------------------------------------- ----------
### WARP multi-function VPS one-click script interface diagram
![43bb749b327c7e3bd5c03f927f3a69d](https://github.com/yonggekkk/warp-yg/assets/121604513/61d2d6c0-9594-4799-9188-084bad886a66)

-------------------------------------------------- ----------
#### Backup of the above script source code [Gitlab address](https://gitlab.com/rwkgyg/CFwarp)
#### Thanks to WGCF source project code address: https://github.com/ViRb3/wgcf
#### Thanks to CoiaPrant, WARP-GO source project code address: https://gitlab.com/ProjectWARP/warp-go
#### Reference sources for related functions: [P3terx](https://github.com/P3TERX/warp.sh), [fscarmen](https://github.com/fscarmen/warp), [enthusiastic CF netizens ](https://github.com/badafans) Warp endpoint preferred IP script and registration procedure

-------------------------------------------------- ---
### Thank you for the star in the upper right corner🌟
[![Stargazers over time](https://starchart.cc/yonggekkk/warp-yg.svg)](https://starchart.cc/yonggekkk/warp-yg)
