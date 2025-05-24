arduino-uno-double-tracking-poc
===============================
### Idea
```c++
void setup() {
  Serial.begin(9600);
}

void loop() {
  // A0 and A1 receive same analog data but preprocess by 2 identical analog circuits
  Serial.print(analogRead(A0));
  Serial.print(",");
  Serial.println(analogRead(A1));
  
  delay(2);
}
```
