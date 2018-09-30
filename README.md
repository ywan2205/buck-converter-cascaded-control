# buck-converter-cascaded-control

This is my final year project/ Thesis. It is basically the implementation of a conventional control method called "cascaded control" on arduino UNO board. 
Arduino UNO board is easy to get and it also provides 100kHz PWM signal I required.
so i didn't bother to use a TI DSP controllers which may takes me monthes to learn. 
Another reason of using arduino is that it's simple to learn. As a result my project may attact newstarters studying in the area of power converter control. This project may help them save some time.

Notice: you should first adjust your PID library downloaded from Arduino library. The default sampling period of PID library is in millisecond which is unacceptable for power converter control. Basically you need to adjust everything relate to millisecond to microsecond.
