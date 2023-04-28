# LED-manipulation-2.0
// C++ code
//
int temp = 0;

void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);

  temp = 1000;
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
