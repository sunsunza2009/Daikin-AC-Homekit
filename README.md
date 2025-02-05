<a><img src="https://i.ibb.co/t2Cj0Lb/73554699-10218936426109092-1041828279960469504-n.jpg" alt="55489249-10217207119037496-5023647251256311808-n" border="0"></a>

# Daikin-AC-Homekit by Homekit Italia Group

[![Download](https://img.shields.io/github/downloads/curla92/Daikin-AC-Homekit/total?color=red
)](https://github.com/curla92/Daikin-AC-Homekit/releases) [![Latest](https://img.shields.io/github/v/tag/curla92/Daikin-AC-Homekit?color=green&label=Latest%20Release
)](https://github.com/curla92/Daikin-AC-Homekit/releases) [![Donate](https://img.shields.io/badge/Donate-PayPal-blue)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=WKPEBA4PLFKXU&source=url) 

A firmware for ESP8266 to control Daikin Air Conditioner. 
You can set heat and cool temp in homekit, control fan speed and swing in EVE app.

**Daikin AC Supported**
Data from [IRremoteESP8266 Supported Protocols](https://github.com/crankyoldgit/IRremoteESP8266/blob/master/SupportedProtocols.md)
- *Daikin ARC433-- remote (DAIKIN);*
- *Daikin ARC466A12 remote (DAIKIN);*
- *Daikin ARC466A33 remote (DAIKIN);*
- *Daikin FTXM-M A/C (DAIKIN);*
- *Daikin M Series A/C (DAIKIN);*
- *Daikin ARC480A5 remote (DAIKIN160);*
- *Daikin ARC423A5 remote (DAIKIN152);*
- *Daikin ARC433B69 remote (DAIKIN216);*
- *Daikin ARC484A4 remote (DAIKIN216);*
- *Daikin FTQ60TV16U2 remote (DAIKIN216);*

**Hardware**

- IR Transmitter;
- DHT22;

**WiKi**

*Go to the [Wiki](https://github.com/curla92/Daikin-AC-Homekit/wiki/EVE-CONFIG) to config.*

**Homekit Setup Code is :**
```
277-66-227
```

<a><img src="https://i.ibb.co/9HHnmK1/qrcode.png" alt="homekit-setpup-code" border="0"></a>

The project is based on accessory server library ESP-HomeKit from [@MaximKulkin](https://github.com/MaximKulkin) for ESP-OPEN-RTOS.
Also it uses the OTA update system [Life-Cycle-Manager (LCM)](https://github.com/HomeACcessoryKid/life-cycle-manager) from [@HomeACcessoryKid](https://github.com/HomeACcessoryKid).

A special thanks to [@GPL71](https://github.com/GPL71) , [@lizzus](https://github.com/lizzus) for their support.

Some code strings come from [@RavenSystem](https://github.com/RavenSystem/esp-homekit-devices) work. I'd like to thank him to help the community to develope.
