# rodi-pcb
Schematic and board files for RoDI (Robot Didáctico inalámbrico)

## Pin assignment

### Ultraonic Sensors (HC-SR04)

| Module        | ATEMGA328 Pin Name | Arduino Pin Name |
| ------------- | :-------------:    | :-------------:  |
| LEFT_US_TRIG  | PC3                | A3               |
| LEFT_US_ECHO  | PD2                | 2                |
| CENTER_US_TRIG| PB4                | 12               |
| CENTER_US_ECHO| PC0                | A0               |
| RIGHT_US_TRIG | PB1                | 9                |
| RIGHT_US_ECHO | PB2                | 10               |

### IMU (MPU6050)

| Module        | ATEMGA328 Pin Name | Arduino Pin Name |
| ------------- | :-------------:    | :-------------:  |
| IMU_SDA       | PC4                | A4               |
| IMU_SCL       | PC5                | A5               |

### Leds and buzzer

| Module        | ATEMGA328 Pin Name | Arduino Pin Name |
| ------------- | :-------------:    | :-------------:  |
| WS2812b       | PB3                | 11               |
| USER_LED      | PB5                | 13               |
| BUZZER        | PD7                | 7                |

### Servos and Hall effect sensors

| Module        | ATEMGA328 Pin Name | Arduino Pin Name |
| ------------- | :-------------:    | :-------------:  |
| LEFT_SERVO    | PD4                | 4                |
| RIGHT_SERVO   | PD5                | 5                |
| LEFT_HALL     | PD3                | 3                |
| RIGHT_HALL    | PD6                | 6                |

### Analog
| Module        | ATEMGA328 Pin Name | Arduino Pin Name |
| ------------- | :-------------:    | :-------------:  |
| BATTERY_MON   | PC2                | A2               |
| LEFT_LINE     | PC1                | A1               |
| RIGHT_LINE    | ADC6               | A6               |
| LDR           | ADC7               | A7               |
