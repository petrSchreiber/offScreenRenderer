# offScreenRenderer
Reusable unit for off screen rendering via OpenGL

## What is it good for?
You can use the offScreenRenderer8b UDT for various tasks, for example:
* rendering image larger than the screen
* simplistic anti-aliasing to your application

## How to use?
The possible example of usage is provided by the *demo.tbasic* example.

![Output of the demo program](https://github.com/petrSchreiber/offScreenRenderer/blob/master/media/output.png "Output of the demo program")

Basically, it is needed to setup #includedir and then include the main file, *offScreenRenderer8b.tbasicu*.

It provides you with super charged UDT, which has methods to setup, use and teardown the off-screen renderer.

*Developed in [thinBasic](http://www.thinbasic.com/)*
