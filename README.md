# final-code

//THE PROMISE
Vroom();
Raven();
Slapper();

int main();
{//Begin int

//

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
{
  enable-servo();
  set_servo_position(servonum, angle);
  disable_servos();
}
