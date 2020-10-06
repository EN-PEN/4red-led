方案一(土法煉鋼) (如同第一次做的)
void setup() {<br>
  // put your setup code here, to run once:<br><br>
pinMode (1,OUTPUT);<br>
pinMode (2,OUTPUT);<br>
pinMode (3,OUTPUT);<br>
pinMode (4,OUTPUT);<br>
}<br>

void loop() {<br>
  // put your main code here, to run repeatedly:<br>
digitalWrite(1,LOW);<br>
digitalWrite(2,LOW);<br>
digitalWrite(3,LOW);<br>
digitalWrite(4,LOW);<br>
delay(100);<br>


digitalWrite(1,HIGH);<br>
digitalWrite(2,HIGH);<br>
digitalWrite(3,HIGH);<br>
digitalWrite(4,HIGH);<br>
delay(100);<br>
}<br>


方案二(迴圈)
```C++
void setup() {<br>
  // put your setup code here, to run once:<br>
for(int i=2;i<6;i++)(設定變數)(遞增)(2~6)<br>
pinMode (i,OUTPUT);(設定MOD繳為OUTPUT)<br>
}<br>

void loop() {<br>
  // put your main code here, to run repeatedly:<br>
  for(int i=2;i<6;i++)(遞增)(2~6)<br>
  digitalWrite(i,LOW);(暗)<br>
delay(300); (延遲)(遞增)(2~6)<br>
   for(int i=2;i<6;i++)<br>
  digitalWrite(i,HIGH);(亮)<br>
delay(300);(延遲)<br>
}<br>
```


圖如下:![image](https://github.com/EN-PEN/4red-led/blob/master/IMG20200908142656.jpg)
