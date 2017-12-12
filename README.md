# DrawBot
This is a repo for a CNC plotter that I'm making. The whole project is mostly based off of this one seen here:
http://www.buildlog.net/blog/2017/10/the-midtbot-a-new-flavor-of-h-bot/

I compiled grbl for the Arduino Nano according to this link:
https://github.com/gnea/grbl/wiki/Compiling-Grbl

The program space of the Nano is expanded using the instructions at this link:
http://www.buildlog.net/blog/2017/09/getting-more-program-space-on-an-arduino-nano/

The controller I'm using is this one here:
https://www.tindie.com/products/33366583/penlaser-bot-controller/

The grbl firmware must be modified as shown here:
http://www.buildlog.net/blog/2017/08/using-grbls-spindle-pwm-to-control-a-servo/
in order to control the z axis servo using the PWM pin. However, the code shown here proved to be incorrect.
I have the fixed version in this repo. 
