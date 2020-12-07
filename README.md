# BasicArduinoTeach

## Hello Arduino

### Description

This assignment was to make an LED blink

### Link to code

[Link to code](https://create.arduino.cc/editor/OneCHSEngr/5cfb671e-4c5f-4411-ac0c-da4f684c9778/preview)

```C++

/*
  Mr. Dierolf
  make an led blink
  12/4/2020
*/

void setup() {
  // this is a comment
  Serial.begin(9600);
  pinMode(13, OUTPUT);

}

void loop() {
  digitalWrite(13, HIGH);
  Serial.println("On");
  delay(500);
  digitalWrite(13, LOW);
  Serial.println("Off");
  delay(500);
}

```

### Wiring diagram

### Reflection
