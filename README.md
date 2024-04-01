## Setup


- Wiring  

| ESP32    | LD2410           | 
|----------|------------------|
| 3.3V     | Vcc |
| GND      | GND |
| [TX] 32  | RX |
| [RX] 33  | TX |


- Building & flashing  
This project was setup with the platformIO extension (VS Code).

- Logging/monitoring  
2 UARTs are setup:  
    - One for the sensor setup (baudrate: 256000)
    - One for logging (baudrate: 115200)