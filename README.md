# Neptune-4-Max---Power-usage-tests
Tests of how much Power the N4Max uses for various operations it can do.
This is to check, and demonstrate, how the stock "400W" N4Max power supply
is inadequate to do the required job properly, reliably, and with load
leeway to allow decent stability in the Voltage.

I ran through a whole bunch of N4Max operations to measure what Power amount
is used for each, but also when many functions operate at the same time.
Only for combinations that you WOULD encounter during use of the N4Max.


Elegoo Neptune 4 Max - Power usage
==================================
All the listed power numbers are the TOTAL USED at any given time/test.

1.  Powered on, fully booted, and sitting idle:
    17.0 W
  	The X,Y,Z Axis have not been Homed, so the Stepper Motors are not in
   	"Hold" mode now, thus less total power is in use - for now.
	
2.	Hotend Target 200degC - Max Heating being used:
  	75W, reducing to 65W quite quickly.
  	It takes less than one minute to reach Target Temp and then uses approx:
  	37W in short runs, to maintain the Target Temp.

3.	Heated Bed Target 60degC - Max heating being used.
  	375W, reducing to 360W quite quickly as it heats up.
  	It takes 6.5 Mins to reach target and uses 350W reducing to 320W for the 
  	majority of the way.

4.	BOTH the Hotend and the Heated Bed operating. Hotend 200DegC, Bed 60degC:
	

5.  Home ALL.  The X&Y Axis move together, but then only the Z Axis moves to 
    complete this:
  	40W
	
6.  Idle Power when the Steppers are being HELD, which is the more normal
    state they are typically in. Once Homed the Steppers are left "Held":
  	30W
	
7.	X or Y Axis motion - medium speed. Each Stepper Motor uses 5W - 7W more
  	than at "hold" to move at a medium speed pace.

8.	Z Axis motion. The Z Axis only uses 1W more than for HOLD, when moved.

9.	One typical printing case. A reasonably large object that then uses
  	reasonably large X & Y Axis moves:
	
	
10.	One typical printing case. A reasonably small object that then uses
  	reasonably small X & Y Axis moves:
	
	
