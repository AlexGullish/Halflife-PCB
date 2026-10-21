# Starbie 

A digital pet built around a **Seeed XIAO ESP32-C3**.

## Features

-   Animated 32 × 32 pixel pet 
-   Tilt-controlled radial menu with four actions: **NAP**, **PLAY**,
    **FEED**, and **PET**.
-   Two physical buttons for menu confirmation and pet stats.
-   Pet stats for joy, energy, and fullness.
-   Motion/shake reaction.
-   Sleep, movement, jumping, and heart effects.
-   DHT11 temperature readings, which can affect the pet's mood.
-   Persistent pet settings

## Controls

| Input | Function |
|---|---|
| **Button 1** | Opens the radial menu and confirms the selected action. |
| **Button 2** | Shows or hides Starbie's stats: joy, energy, and fullness. |
| **Tilt** | Moves the radial menu selection between NAP, PLAY, FEED, and PET. |
| **Shake** | Triggers a reaction and changes Starbie's stats. |

### Radial menu actions

| Action | Effect |
|---|---|
| **NAP** | Starbie naps and recovers energy. |
| **PLAY** | Starts a play animation and affects Starbie's stats. |
| **FEED** | Feeds Starbie and restores fullness. |
| **PET** | Gives Starbie affection and increases joy. |

Select PET three times to unlock a hidden reaction.

<img width="1464" height="1064" alt="image" src="https://github.com/user-attachments/assets/4ac9a20d-1b1f-4fa0-bb26-e405fe159af8" />

<img width="1318" height="1064" alt="image" src="https://github.com/user-attachments/assets/f7fe36d4-5bd8-4a9b-9369-cd4e10bef6f0" />


## BOM
| Item              | Qty | Supplier     | Cost/item | Total Cost | Link                                                                                                                                                                                                                                                                                                                                                                                                                                                 |   |
|-------------------|-----|--------------|-----------|------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---|
| OLED              | 1   | BerryBase    | $8.20     | $8.20      | https://www.berrybase.ch/en/1.3-128x64-oled-display-module-single-colour-blue-spi-i2c-interface-vertical-pin-header                                                                                                                                                                                                                                                                                                                                  |   |
| MPU 6050          | 1   | Amazon       | $6.98     | $6.98      | https://www.amazon.com/Wishiot-MPU-6050-Accelerometer-Gyroscope-Converter/dp/B0C3LDTTBJ?dib=eyJ2IjoiMSJ9._zRQIjLy8SJUb458TCsORetJgOfbFuZygfVdp0jxk34bobJYxcCET9ZKo2ZIjJmWwoVwIGVx7ZHQtCuZ8lxhPdDJgTMchD72SZbX7_gADpVgQRINv9Yntp1f5SWZtD32cBRzmLcA0oXt_Qdg16pTw3wSQuJebnQZld4aCFmDqOKxbRcdQZWLawOwqldtDbAyASD-vnyRJBVbXghbnCjyX2qR8vWZ4UfXSNIvHhu6Au0.7I4zY03kIePsyJjJuE0HxgEnDAcv7tHNtNGlewJVsA0&dib_tag=se&keywords=mpu-6050&qid=1792541802&sr=8-19 |   |
| 10k               | 1   | BerryBase    | $0.06     | $0.06      | https://www.berrybase.ch/en/metal-film-resistor-1.0-kohm-1-4w-1-0207-axial-through-hole-mounting                                                                                                                                                                                                                                                                                                                                                     |   |
| Cherry Switches   | 2   | BerryBase    | $1.32     | $2.64      | https://www.berrybase.ch/en/cherry-mx-blue-pushbutton-module-pcb-fixing-pin                                                                                                                                                                                                                                                                                                                                                                          |   |
| DHT11             | 1   | Bastelgarage | $4.70     | $4.70      | https://www.bastelgarage.ch/sensoren/temperatur/dht11-temperatur-und-luftfeuchtigkeitssensor                                                                                                                                                                                                                                                                                                                                                         |   |
| XIAO-ESP32-C3-SMD | 1   | Seeed Studio | $4.90     | $4.90      | https://www.seeedstudio.com/Seeed-XIAO-ESP32C3-p-5431.html                                                                                                                                                                                                                                                                                                                                                                                           |   |
| PCB               | 1   | JLCPCB       | $4.00     | $4.00      | https://cart.jlcpcb.com/quote?stencilLayer=2&stencilWidth=100&stencilLength=100&stencilCounts=5&plateType=1&spm=Jlcpcb.Homepage.1010                                                                                                                                                                                                                                                                                                                 |   |
| Total Cost                   |     |              | $31.48      |            |                                                                                                                                                                                                                                                                                                                                                                                                                                                      |   |


Keycaps will also be used but they do not need to be newly purchased 
