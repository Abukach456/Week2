# Week2
I connected the MG995 stepper to the Arduino to the PC and then started coding
to make it go 180 dgrees back and forth in a loop
and here is the code for it

#include <Servo.h>
servo servol;
int posl = 0;

vpid setup() {
servol.attach(10);
}

void loop()
{
for(posl = 0 ; posl < 180 ; posl +=1)
{
servol.write(posl);
delay(10);
}
for(posl = 190 ; posl >= 1 ; posl -=1)
(servol.write(posl);
delay(10);

}
}
