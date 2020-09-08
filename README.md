方案一
void setup() {
  // put your setup code here, to run once:
pinMode (1,OUTPUT);
pinMode (2,OUTPUT);
pinMode (3,OUTPUT);
pinMode (4,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
digitalWrite(1,LOW);
digitalWrite(2,LOW);
digitalWrite(3,LOW);
digitalWrite(4,LOW);
delay(100);


digitalWrite(1,HIGH);
digitalWrite(2,HIGH);
digitalWrite(3,HIGH);
digitalWrite(4,HIGH);
delay(100);
}


方案二(迴圈)
void setup() {
  // put your setup code here, to run once:
for(int i=2;i<6;i++)
pinMode (i,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  for(int i=2;i<6;i++)
  digitalWrite(i,LOW);
delay(300); 
   for(int i=2;i<6;i++)
  digitalWrite(i,HIGH);
delay(300);
}



圖如下:
