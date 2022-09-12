BLE Catcher will get IoT data from sensors using BLE, and then send the data periodically to Home Assistant

The project is split in two:
- A service taht will periodically catch the temperature, maybe launched via cron
- An actix web server that will get the temperature from a file on the disk and will answer HomeAssitant requests