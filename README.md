# PBC.sh [![Bash4.2-shield]](http://tldp.org/LDP/abs/html/bashver4.html#AEN21220) [![License-shield]](https://raw.githubusercontent.com/v1s1t0r1sh3r3/airgeddon/master/LICENSE.md)       

       
[![image1]]   

# **Dependencies**    

I would say "none" as the script uses only fundamentals linux Newtork/WiFi Tools/Commands.
 * **Bash** (PBC.sh is a bash script) 
 * **wpa_suppliant** (and its "interactive comand line": **wpa_cli**) 
 * **Network Manager** (and its "inetractive command line util": **nmcli**)

 
# **How to use it?**    
 - Clone this repository
```
git clone https://github.com/kcdtv/PBC.git
```   
 - Locate your shell in the downloaded branch   
```
cd PBC
```
 - Launch the script invoking bash with administrador privileges
```
sudo bash PBC.sh
```

# **What does it does?**     
 - When you execute **PBC.sh**; a WPS conexion request is sent in **P**ush **B**utton **C**onfiguration mode using **wpa-cli**       
[![image2]]   
 - You just have to press the PBC button from your **A**ccess **P**oint in order to connect to it          
[![image3]]   
 - The script automaticaly exports the datas from **wpa_supplicant** to create a profile for **Network Manager** in order to restart it and to do the final connexion with it.
 
For more information visit: https://www.wifi-libre.com/
 
[image1]: https://www.wifi-libre.com/img/members/3/PBCsh_1.jpg
[Bash4.2-shield]: https://img.shields.io/badge/bash-4.2%2B-blue.svg?style=flat-square&colorA=273133&colorB=00db00 "Bash 4.2 or later"
[License-shield]: https://img.shields.io/badge/license-GPL%20v3%2B-blue.svg?style=flat-square&colorA=273133&colorB=bd0000 "GPL v3+"   
[image2]: https://www.wifi-libre.com/img/members/3/PBCsh_2.jpg
[image3]: https://www.wifi-libre.com/img/members/3/PBCsh_4.jpg
