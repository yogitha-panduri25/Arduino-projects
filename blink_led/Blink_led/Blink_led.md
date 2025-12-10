# Blink LED Project

This is my first Arduino project.  
It blinks an LED connected to pin 13 on the Arduino UNO.

## Components
- Arduino UNO
- LED
- 220Ω resistor
- Jumper wires

## Circuit
LED positive → Pin 13  
LED negative → GND  
(Use 220Ω resistor in series)

## Code
```cpp
void setup() {
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);
}
