# 🔌 Wiring Overview – LuminPlant

## ESP32 Pin Mapping

| Pin (ESP32) | Function         | Connected Module     |
|-------------|------------------|-----------------------|
| GPIO4       | WS2812 LED Ring  | Plant light           |
| GPIO36      | Analog In (ADC1) | Ambient light sensor (LDR) |
| GND         | Ground            | All modules           |
| 5V / VIN    | Power supply      | LED ring + LDR sensor |

## Note:
The LDR sensor is connected via a voltage divider using a 330Ω resistor.
