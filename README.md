# 12-1
void setup() {
  // put your setup code here, to run once:
   pinMode(2, OUTPUT);
   pinMode(3, INPUT);
   pinMode(4, INPUT);

}

void loop() {
  // put your main code here, to run repeatedly:
   if (digitalRead(3)==0)
   {
    digitalWrite(2, HIGH);
    delay(100);
   }
      if (digitalRead(4)==0)
   {
    digitalWrite(2, LOW);
    delay(100);
   }

   
   

}
