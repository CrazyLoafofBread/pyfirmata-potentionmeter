# pyfirmata-potentionmeter
Potentiometer value input in arduino using pyfirmata

This code requires the pyfirmata library, you can install it in terminal with the command: "pip install pyfirmata"

Also you can find a picture to understad the circuit
C++ code for the arduino IDE:
// C++ code
//
void setup()
{
  pinMode(A0, INPUT);
  pinMode(9, OUTPUT);
}

void loop()
{
  float potentionmeterinput = analogRead(A0);

  digitalWrite(9, potentionmeterinput);
  delay(10); // Delay a little bit to improve simulation performance
}
