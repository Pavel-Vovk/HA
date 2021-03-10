# Home Assistant Configuration

The configuration of the private Home Assistant server. 

The HA server have been running in docker containers.

The docker have been running on Raspberry PI 4B 8 GB.

The configurations are stored in the separated files and folders in order to manage the different entities in separated files.

## Devices:
- Raspberry PI 4B 8 GB
- MikroTik Router RB4011iGS+ 
- MikroTik Access Point cAP ac RBcAPGi-5acD2nD.
- ESP32 nodemcu-32s 1 pcs + BPM280 + SHT30
- ESP32 m5stack-core-esp32 2 pсs + BPM280 + SHT30
- Xiaomi IR Remote (chuangmi-remote-h102c01, CMYCq01C) 2 pсs
- LG TV 42LM340T TV Remote Control
- Samsung TV
- Xiaomi Mijia Digital Clock 3.7" E-INK Screen Temperature Humidity Sensor Meter (LYWSD02) 2 pcs
- TBD

## Additional
- Telegramm
  - Auto Notification (restart/reboot)
  - Statuses. 
  - Remote commands (could be closed in github public access) 

## Example with Screenshots
1. [Network](includes/views/network.yaml)

![Network](https://github.com/Pavel-Vovk/HA/blob/master/image/home_assistant1.png)

2. [Network-Traffic](includes/views/network_traffic.yaml)

![Network-Traffic](https://github.com/Pavel-Vovk/HA/blob/master/image/home_assistant2.png)

3. [HA Details](includes/views/homeassistant.yaml)

![[HA Details](https://github.com/Pavel-Vovk/HA/blob/master/image/home_assistant3.png)

4. [Cabinet](includes/views/esp32_room2.yaml)

![Cabinet](https://github.com/Pavel-Vovk/HA/blob/master/image/home_assistant4.png)

5. [Living Room](includes/views/living_room.yaml)

![Living Room](https://github.com/Pavel-Vovk/HA/blob/master/image/home_assistant5.png)

6. [Remote LG TV](includes/views/tv_remote.yaml)

![Remote LG TV](https://github.com/Pavel-Vovk/HA/blob/master/image/home_assistant6.png)

