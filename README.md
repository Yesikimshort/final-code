# final-code-Son

//THE PROMISE
Vroom();
Raven();
Slapper();

int main()
{//Begin int

//The robot will move towards the ramp to pull out the transport
Vroom(80,80,1500);
//The robot reached the transport, it will now turn to face it
Vroom(80,-80,1000);

//The robot will now close on the transport
Slapper(0,intangle);
Slapper(3,intangle);

The robot will now pull the transport and place in under the water
Vroom(-80,80,1500);
//Robot turned left
Vroom(-80,-80,1500);
//The robot vroom'd backwards
Vroom(80,-80,1500);
//Robot turned right
Vroom(80,80,1500);
//Robot moved the transport under the robot

Slapper(0,0);
Slapper(3,0);
//Robot let go of transport

Vroom(-80,-80,1500)
//Robot went backwards for his journey back on the ramp
Vroom(-80,80,1500)
//Robot turned to face the ramp
Vroom(80,80,1500)
//RObot went forward towards the lamp
Vroom(80,-80,1500)
//Robot turned right to face the ramp

Vroom(80,80,1500)
//Robot goes up ramp
Vroom(80,-80,1500)
//Robot turned left
Vroom(80,80,1500)
//Robot moves forward



ao();
}//End int

//THE DEFINITION
//Moving Wheels
void Vroom(int rwheel,int lwheel, int time)
{//Moving wheels
  mav(0, rspeed);
  mav(3, lspeed);
  msleep(timer);
  }//End void

//Follow the blackline
void Raven(int counter, int black)
{//Begin void
  cmpc(0); //clears the motor position counter while (gmpc(0) < counter)
  {//Begin while
  while (analog(1)>black)
    {//Begun while 2
      Vroom(500,100,100);//turn left if black
      printf("left/n");
    }//End While 2
    while(analog(1)<black)
    {//start while 3
      Vroom(100,500,100);
      printf("right\n");
    }//End while 3
  }//End While
}//End Void

//Servo MOvement
Void Slapper(int servonum, int angle)
{//Begin void
  enable-servo();
  set_servo_position(servonum, angle);
  disable_servos();
}//End void




HEREEEEEEEEEE

#include <kipr/botball.h>
#include "Alexandria.h"

//wait_for_light(0);
//shut_down_in(115);

int main()
{//Begin int
    printf("Hello World\n");
	
    //Task 1
    Slapper(0,0);
    //Vroom(1000,1000,3200);
    //Move forward
	//Vroom(550,0,1800);
    //Move to the left
    //Vroom(900,600,1500);
    //Vroom(500,800,3000);
    //Vroom(-500,-500,2000);
    //Vroom(600,500,1500);
    //Vroom(600,700,1500);
    //Vroom(-600,-600,4500);
    //Vroom(-600,0,3000);
    //Vroom(-600,-800,3000);
    //Vroom(600,400,3000);

    
	//Vroom(1000,1000,2000);
    //Slapper(0,0);
    //Vroom(1000,0,1800);
    //Vroom(500,500,1500);
    //Vroom(0,500,1500);
    //Vroom(-500,-500,1000);
    //Vroom(500,0,1500);
    //Vroom(0,1000,1000);
    //Vroom(-1100,-1000,3000);
    //Vroom(-800,0,1500);
    //Vroom(-800,-800,4500);
    //Vroom(800,-1000,1000);
    //Vroom(800,1000,2000);
    //Vroom(-500,-500,1000);
    //Vroom(500,500,2000);
 
    printf("Lowered My Arm\n");
	printf("I will begin my terror\n");

	while (analog(1)<3000)
	{//Start While
	Vroom(1000,1000,5000);
	}//End While
	printf("Detected Black line");

    Vroom(500,0,1500);
    Vroom(800,800,3000);
    printf("Push number one complete/n");
    Vroom(500,700,1500);
    Vroom(800,600,3000);
    printf("Push number two complete/n");
    //Task one completed
    
    //Task 2
    printf("Completing task 2/n");
    Vroom(-800,-600,3000);
    Vroom(500,0,1000);
    Vroom(1000,1000,5000);
    Vroom(500,500,2000);
    Slapper();
    printf("Poms and pole collected/n");
    
    Vroom(-500,-500,1500);
    Vroom(0,-500,1500);
    Vroom(800,800,1000);
    Vroom(-500,0,1500);
    Vroom(500,500,1500);
    Slapper();
    printf("Second poms and pole/n");
    
    printf("Place in place/n");
    Vroom(-500,-500,1500);
    Vroom(0,1000,2000);
    Vroom(800,800,25000);
    Vroom(0,800,1500);
    Vroom(1000,1000,3000);
    
    cmpc(0);
    while(gmpc(0)<2200)
    {
        Vroom(2000,0,0);
        msleep(500);
        Vroom(0,2000,0);
        msleep(500);
    }
    //Task 2 over
    
   
    //Task 3 commence
    printf("Task number 3/n")
    Vroom(-1000,-1000,2600);
    Vroom(0,800,1500);
    
