# BurpAndroidOneLiner 🦉

Instead of setting up a burp certificate on Android manually which takes some time, here is a one liner for automating this process.

Used Genymotion & Android V10.


# Requirements

  Burp:
  
    https://portswigger.net/burp/releases


  frida-server: 
  
    https://github.com/frida/frida/releases
  
  Frida tools: 
  
    pip install frida-tools
 
  Install open ssl for Mac:
    
    brew install openssl
  
  Install open ssl for Linux:
  
    sudo apt-get install libssl-dev


# Installation 🦄
```
  git clone https://github.com/TheSerialiZator/BurpAndroidOneLiner
  
  cd BurpAndroidOneLiner
  
  chmod +x automate.sh
  
  ./automate.sh
 ```

