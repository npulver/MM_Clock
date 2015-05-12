# MM_Clock
Arduino controlled LCD clock
Go to http://transelectricdesign.com/2015/05/maker-monday-clock-part-iv/ for details of the project.
Parts needed:
Arduino ProMini
16x2 RGB LCD Display
FTDI Programmer
Normally Open Pushbutton

1. Download and extract the MM_Clock file.
2. Open the "Clock Code" text document in a text editor
3. Copy and paste code into Arduino IDE
4. In the Arduino IDE, open a new tab and name it "Font_helper"
5. Open the "Font Helper" text document in a text editor.
6. Copy and paste Font Helper code in the "Font_helper" tab in the Arduino IDE
7. Upload and enjoy!

Pushbutton is used to change the time.  In this current revision, the "m" variable advances once per second.  
At this rate, it takes 1 minute to advance the clock 1 hour.
The next revision should include code to speed up this transition.
