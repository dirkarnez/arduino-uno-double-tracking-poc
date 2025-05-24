arduino-uno-double-tracking-poc
===============================
### Idea
```c++

void setup() {
  // initialize serial communications at 9600 bps:
  Serial.begin(9600);
}

void loop() {
  // read the analog in value:
  // sensorValue = ;
  // map it to the range of the analog out:
  //outputValue = map(sensorValue, 0, 1023, 0, 255);

  Serial.print(analogRead(A0));
  Serial.print(",");
  Serial.println(analogRead(A1));
  
  delay(2);
}
```
