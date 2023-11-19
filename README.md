# Neptune-4-Max---Power-usage-tests

Elegoo Neptune 4 Max - Power usage
==================================
All the listed power numbers are the TOTAL USED at any given time/test.
The N4Max has a "400W" power supply unit. The real manufacturer of that
recommends only running their power supplies at 80% of the rated value.
That means only using a maximum of 320W from a "400W" rated power supply!

The real "typical" maximums are going to be when the Hotend AND Bed are
being heated up, at the same time. You typically would NOT be printing at
this time. But you yourself MIGHT happen to Home the printer at that same
time - which would add some small extra power amount to the total.

You can see that the N4Max run WAY over the manufacturer recommended maximum
of 320W !!! Even though it does NOT exceed the "400W" rating, it takes it
well into the high power regions where it will not be able to keep ripple,
noise levels low, or heat, and Voltage stability and the units lifespan
will be detrimentally affected.
This "400W" is NOT TRULY ADEQUATE for the N4Max!!!
To operate a power supply with the recommended 20% leeway, and thus much
better efficiency and Voltage stability, you would need to use the "600W"
model. In End Used dollar cost, the difference between the cost of the
"400W" model and the "600W" model is only about US$7 !! Or outright cost
of the "600W" is about US$25 region.
Technically you should BUY A "600W" model and change out the stock "400W"
one!


1. Powered on, fully booted, and sitting idle:

   17.0 W

   The X,Y,Z Axis have not been Homed, so the Stepper Motors are not in
   "Hold" mode now, thus less total power is in use - for now.
	
2. Hotend Target 200degC - Max Heating being used:
   
	 75W, reducing to 65W quite quickly.
   
	 It takes less than one minute to reach Target Temp and then uses approx:

   37W in short runs, to maintain the Target Temp.

3. Heated Bed Target 60degC - Max heating being used:

   375W, reducing to 360W quite quickly as it heats up.
   
	 It takes 6.5 Mins to reach target and uses 350W reducing to 320W for the 
	 majority of the way.

4. BOTH the Hotend and the Heated Bed operating. Hotend 200DegC, Bed 60degC:
	

5. Home ALL.  The X&Y Axis move together, but then only the Z Axis moves to 
   complete this:

   40W
	
6. Idle Power when the Steppers are being HELD, which is the more normal
   state they are typically in. Once Homed the Steppers are left "Held":

   30W
	
7. X or Y Axis motion - medium speed. Each Stepper Motor uses 5W - 7W more
	than at "hold" to move at a medium speed pace.

8. Z Axis motion. The Z Axis only uses 1W more than for HOLD, when moved.

9. One typical printing case. A reasonably large object that then uses
	 reasonably large X & Y Axis moves:

   Heating:

   Printing:
	
11.	One typical printing case. A reasonably small object that then uses
	  reasonably small X & Y Axis moves:
	
	  Heating:

    Printing:


	
	
