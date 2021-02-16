# Feel-The-Music
Device That Helps Hearing Impaired Feel Music Through Vibrations and a Light Show 
The device is simple - it uses an omni-directional microphone with auto gain control to pick up sounds from the environment and converts these signals to analog voltage output that is fed into the Arduino analog input. 
The Arduino microprocessor is programmed to poll this input port and convert this into digital output. 
Depending on the amplitude of the signal received a particular output port is "lit up". 
These output ports are connected to two types of output devices - a colored LED and a small vibrating motor.
In all I have programmed for four levels - therefore there are 4 colored LEDS and 4 vibrating motors.
I intend to put all this onto one wearable device that is worn on the wrist like a wristwatch
When a hearing impaired person wears this device and music is played in their environment, the device will pick this up and the hearing impaired person will feel the music synchronised vibration on their wrist and they will also see a colored LED display that will be synchronised to the music almost like an equalizer display.
As a further test on what better serves the hearing impaired community, one could do a spectrum analysis on the music (using a different code on the Arduino than the amplitude analysis code that I have) and then drive the LEDs and motors depending on what frequencies are contained in the sound. This will allow the hearing impaired person to get a sense of whether a low pitched instrument like a drum is being played or a higher pitched instrument like a violin is being played.  
