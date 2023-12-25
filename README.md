# Motor-Contro
Control a brushless motor using PWM signals with Arduino.
#define MOTOR_PIN 9

void setup() {
    pinMode(MOTOR_PIN, OUTPUT);
}

void loop() {
    analogWrite(MOTOR_PIN, 128);  // Adjust PWM duty cycle for motor speed control
}
