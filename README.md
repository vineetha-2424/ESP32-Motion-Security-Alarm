int pir = 27;
int buzzer = 26;

void setup() {
  pinMode(pir, INPUT);
  pinMode(buzzer, OUTPUT);
}

void loop() {
  if (digitalRead(pir) == HIGH) {
    digitalWrite(buzzer, HIGH);
  } else {
    digitalWrite(buzzer, LOW);
  }
}
# ESP32-Motion-Security-Alarm
