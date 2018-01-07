# T6963C_libraries_Supports-Arduino_1.8.5_and_later
Graphic LCD with Toshiba T6963 controller  Copyright (c)  Norbert Hidas 2018
Interface Connection                                                           	ARDUINO BOARD PINOUT 		ARDUINO MEGA BOARD

 
PINOUT example for MG24065G-Series
+-------+--------+------------------------------------------------------+
|Pin No.| Signal | Function                                             |
+-------+--------+------------------------------------------------------+
|   1   | FGND   | Frame Ground (Connected to Metal Bezel)              |
+-------+--------+------------------------------------------------------+
|   2   | GND    | POWER SUPPLY (GND)                                   |	GND				GND
+-------+--------+------------------------------------------------------+
|   3   | Vdd    | Power Supply for Logic (+5VDC)                       |	+5V 				+5V
+-------+--------+------------------------------------------------------+
|   4   | Vo     | OPERATING VOLTAGE FOR LCD Drive                      |
+-------+--------+------------------------------------------------------+
|   5   | ~WR    | L: Data Write (LCD Module * * MPU)                   |	Analog pin 0			Digital pin 37
+-------+--------+------------------------------------------------------+
|   6   | ~RD    | L: Data Read (LCD Module * * MPU)                    |	Analog pin 1			Digital pin 36
+-------+--------+------------------------------------------------------+
|   7   | ~CE    | L: Chip Enable                                       |	Analog pin 2			Digital pin 35
+-------+--------+------------------------------------------------------+
|   8   | C/~D   | ~WR="L"; C/~D="H":Command Write, C/~D="L":Data Write |	Analog pin 3			Digital pin 34
|       |        | ~RD="L"; C/~D="H":Status Read  , C/~D="L":Data Read  |
+-------+--------+------------------------------------------------------+
|   9   | VEE    | POWER SUPPLY FOR LCD DrivING OUTPUT                  |
+-------+--------+------------------------------------------------------+
|  10   | ~RES   | L: Module Reset (Controller Reset)                   |	  RESET Pin 			  RESET Pin
+-------+--------+------------------------------------------------------+
|  11   | D0     | Data Input/Output (LSB)                              | 	Digital pin 2			Digital pin 49
+-------+--------+------------------------------------------------------+
|  12   | D1     | Data Input/Output                                    | 	Digital pin 3			Digital pin 48
+-------+--------+------------------------------------------------------+
|  13   | D2     | Data Input/Output                                    | 	Digital pin 4			Digital pin 47
+-------+--------+------------------------------------------------------+
|  14   | D3     | Data Input/Output                                    | 	Digital pin 5			Digital pin 46
+-------+--------+------------------------------------------------------+
|  15   | D4     | Data Input/Output                                    | 	Digital pin 6			Digital pin 45
+-------+--------+------------------------------------------------------+
|  16   | D5     | Data Input/Output                                    | 	Digital pin 7			Digital pin 44
+-------+--------+------------------------------------------------------+
|  17   | D6     | Data Input/Output                                    | 	Digital pin 8			Digital pin 43
+-------+--------+------------------------------------------------------+
|  18   | D7     | Data Input/Output (MSB)                              | 	Digital pin 9			Digital pin 42
+-------+--------+------------------------------------------------------+
|  19   | FS     | TERMINALS FOR SELECTION OF COLUMNS                   |             Changeover switch    --o Ground
|       |        | H:6 * 8 Font       L:8 * 8 Font                      |                    FS PIN    ___/
+-------+--------+------------------------------------------------------+                                  --o +5VDC
|  20   | NC     | No Connection                                        |
+-------+--------+------------------------------------------------------+             POTI FOR LCD DRIVING 50KOhm
|  21   | NC     | No Connection                                        |                 +5V ----WW---- VEE
+-------+--------+------------------------------------------------------+                         /
|  22   | NC     | No Connection                                        |                         |
+-------+--------+------------------------------------------------------+                        Vo




Interface Connection                                                           	ARDUINO BOARD PINOUT 		ARDUINO MEGA BOARD


PINOUT example for Hitachi SP14N01L6ALCA
+-------+--------+------------------------------------------------------+
|Pin No.| Signal | Function                                             |
+-------+--------+------------------------------------------------------+
|   1   | VSS    | POWER SUPPLY (GND)                                   |	GND				GND
+-------+--------+------------------------------------------------------+
|   2   | VDD    | Power Supply for Logic (+5VDC)                       |	+5V 				+5V
+-------+--------+------------------------------------------------------+
|   3   | V0(IN) | Power Supply for LCD Drive                           |
+-------+--------+------------------------------------------------------+
|   4   | C/~D   | ~WR="L"; C/~D="H":Command Write, C/~D="L":Data Write |	  Analog pin 3			Digital pin 34
|       |        | ~RD="L"; C/~D="H":Status Read  , C/~D="L":Data Read  |
+-------+--------+------------------------------------------------------+
|   5   | ~WR    | L: Data Write (LCD Module * * MPU)                   |	  Analog pin 0			Digital pin 37
+-------+--------+------------------------------------------------------+
|   6   | ~RD    | L: Data Read (LCD Module * * MPU)                    |	  Analog pin 1			Digital pin 36
+-------+--------+------------------------------------------------------+
|   7   | D0     | Data Input/Output (LSB)                              | 	Digital pin 2			Digital pin 49
+-------+--------+------------------------------------------------------+
|   8   | D1     | Data Input/Output                                    | 	Digital pin 3			Digital pin 48
+-------+--------+------------------------------------------------------+
|   9   | D2     | Data Input/Output                                    | 	Digital pin 4			Digital pin 47
+-------+--------+------------------------------------------------------+
|  10   | D3     | Data Input/Output                                    | 	Digital pin 5			Digital pin 46
+-------+--------+------------------------------------------------------+
|  11   | D4     | Data Input/Output                                    | 	Digital pin 6			Digital pin 45
+-------+--------+------------------------------------------------------+
|  12   | D5     | Data Input/Output                                    | 	Digital pin 7			Digital pin 44
+-------+--------+------------------------------------------------------+
|  13   | D6     | Data Input/Output                                    | 	Digital pin 8			Digital pin 43
+-------+--------+------------------------------------------------------+
|  14   | D7     | Data Input/Output (MSB)                              | 	Digital pin 9			Digital pin 42
+-------+--------+------------------------------------------------------+
|  15   | ~CE    | L: Chip Enable(~CE must be L)                        |  	Analog pin 2			Digital pin 35
+-------+--------+------------------------------------------------------+ 
|  16   | ~RES   | L: Module Reset (Controller Reset)                   |	  RESET Pin 			  RESET Pin
+-------+--------+------------------------------------------------------+
|  17   | VEE    | POWER SUPPLY FOR LCD DrivING                         |
+-------+--------+------------------------------------------------------+
|  18   | ~D.OFF | VDD/Display on , GND/Display off                     |
+-------+--------+------------------------------------------------------+
|  19   | FS     | TERMINALS FOR SELECTION OF COLUMNS                   |             Changeover switch    --o Ground
|       |        | H:6 * 8 Font       L:8 * 8 Font                      |                    FS PIN    ___/
+-------+--------+------------------------------------------------------+                                  --o +5VDC
|  20   | P/N    | Display Mode reverse.                                |
+-------+--------+------------------------------------------------------+             POTI FOR LCD DRIVING 10-20 KOhm
|  21   | NC     | No Connection                                        |                 
+-------+--------+------------------------------------------------------+                +5V -+          +- -15V
|  22   | NC     | No Connection                                        |                     |          |
+-------+--------+------------------------------------------------------+                VDD -+----WW----+- VEE 
|  23   | Y2     | Analog signal digitizer bottom                       | 	                   /
+-------+--------+------------------------------------------------------+                          |
|  24   | X1     | Analog signal digitizer right                        | 	                   V0
+-------+--------+------------------------------------------------------+
|  25   | Y1     | Analog signal digitizer upper                        | 	
+-------+--------+------------------------------------------------------+
|  26   | X2     | Analog signal digitizer left                         |	
+-------+--------+------------------------------------------------------+                        


0.0- What these 2 guys built that I worked from
      Graphic LCD with Toshiba T6963 controller
      Copyright (c) Rados?aw Kwiecie?, 2007r
      http://en.radzio.dxp.pl/t6963/
      Compiler : avr-gcc
      Modified By -rbrsidedn- to work on Arduino easily : http://domoduino.tumblr.com/
       
0.1- Invocable class T6963
      Commands moved to T6963_commands.h
      For some reason I don't have reset hooked up and all is working fine.
0.2- rbrsidedn
      renamed SetPixel(byte,byte,byte) -> writePixel(x,y,color)
      added setPixel(x,y)
      added clearPixel(x,y)
      added createline(x1,y1,x2,y2)
      added createCircle(x,y,radius)       
r6 - Checked in with SVN
r7 - Checked in with cursor controls added
r8 - Got 6bit font width (s/b any fonth width) working.  
r9 - removed T6963_Commands.h
r10 -	remove T6963_Commands.h file
	fixed clearPixel error
	Correcting SVN revision, forgot to upload R9 I guess
r13 - Original from -rbrsidedn1- Features added by big-maec : Text Attribute, Image View with bmp2c, 
      Play Anim with bmp2c, filled Box, String with Font use GLCD_Env_1.3, Demo Sketch(30K Memory needed), ARDUINO MEGA SUPPORT.

r14 - Supports Arduino 1.8.5 and later! (New DECLARATIONS PROGMEM) /creator: Norbert Hidas/


