These questions aim to test our new members without/with a little background in programming and Arduino. There are four questions. They can also be used as a self-learning guidebook.

## Question 1

Get familiar with C++/C syntax. Arduino is commonly controlled by C-like language. So get familiar with it by using the following unfinished code.

**Target:** Find and setup any environment(on your computer or on the Internet) to run a C++ program. The program takes in 2 numbers $a$ and $b$, and outputs their sum.

```c++
#include <iostream>
using namespace std; // which is a bad habit
int main(){
	// write your code here
	return 0;
}
```

## Question 2
Here is a Arduino Uno. You might find a HD version of the picture.

![Arduino](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTX-dGOCE5NBCQA0lL2OqqzkkfTrtraOGTIKw&usqp=CAU)

**Target:** Please find GND and PWM port, and explain their **function** using your language.

## Question 3
You might have get a vague idea about what is C and what is Arduino. But how does the thing work?

<img src="https://github.com/Electronic-Intelligence-Club/funnyQ4admin/blob/main/LED.png" width = "500" alt="demo" align=center />

Here is an illustration of how a LED is connected to Arduino.

**Target:** Find out how the LED is connected exactly. You may need to learn about jumper wire and bread board.

## Question 4
Arduino code and C code share common syntax but they are not same in the logic.

**Target:** Assuming you have connected as LED to Arduino as shown in *Question 3*, read the following code and explain what the code aims to do. Also please explain why we need function `setup` and `loop`.
```c++
int ledPin = 10;
void setup() {
       pinMode(ledPin, OUTPUT);
}
void loop() {
       digitalWrite(ledPin,HIGH);
       delay(1000);
       digitalWrite(ledPin,LOW);
       delay(1000);
}
```
