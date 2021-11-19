# Logitech_F710_GamePad

A simple Python code to use Logitech F710 Gamepad.

Dependencies: PyGame

## How to use
    def GetInput(self,joyL=0,joyR=0,trigL=0,trigR=0,hat=0,buttons=0,
              freq=20,joyL_max=100,joyR_max=100,trigL_max=100,trigR_max=100,os='windows',release_after=2):

To obtain input values from any combination of the input methods (e.g. left/right joysticks, buttons, etc.),
simply set the input parameters to 1.
Optional: The other input parameters allows you to specify the sampling frequency, the range of joysticks, and
the time to automatically release of buttons in seconds. 

Note: depending on the OS the numbering of buttons and joystick may be different. In that case, you can change the 
'os' parameter if it's Ubuntu, or edit line 43-44 to adjust for your use. 
