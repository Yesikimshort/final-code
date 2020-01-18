# final-code-Son

//THE PROMISE
Vroom();
Raven();
Slapper();

int main();
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
