# 775-Condition-Monitoring

End-to-end condition monitoring prototype for a 775 12V DC motor using vibration + current + RPM signals.  
Pipeline: ESP32 -> Raspberry Pi 5 -> MQTT -> Node-RED dashboard.

Full presentation: **[docs/Motor_CM.pdf](docs/Motor_CM.pdf)**

## Photos
![System running](media/system_in_function.jpg)
![ESP32 + RPi5 setup](media/rpi_esp32_working_hardware.jpg)
![Tachometer setup](media/tachometer_setup.jpg)

## Node-RED dashboard + pipeline
![Node-RED flow](media/node-red.png)

## Raspberry Pi live output
![RPi output](media/rpi_output.png)

![Imbalance test](media/imbalance.jpg)
