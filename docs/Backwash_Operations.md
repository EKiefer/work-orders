### Introduction
The rapid sand filter's purpose is to remove any type of flocculation and suspended matter from the water that was not removed in the settling basins and is the last step of physical water treatment.  Filters are controlled in either an “Auto MGD mode” or “Manual MGD mode.”  While in “Auto MGD mode” the operator controls the filter functions through the SCADA system on the computers located by the main control panel.  While operating in “Manual MGD mode” the operator controls the filter functions through the filter control council touch pad. 

Filters are maintained by backwashing regularly after approximately 150 hours of filtering, filters may also need to be backwashed prior to reaching 150 hours if they are; stopped for any reason, experience over 8 feet of head loss or produce filtered water at or above 0.3 NTU.  
***

### Operation Warnings
-While manually backwashing don’t start pumps with valves closed, dead heading.
-Reclaim reservoir overflows at 12.25’
-Don’t draw down other filters, channel level, below 10.2’ effluent valves will close and all filters in service will need to be backwashed. 
***

### Personal Safety
No personal safety hazards are present
***

### Materials, Supplies & Equipment
- Hoze and spray nozzle
***

### Procedure

- <u>Auto filter backwash</u>
	- Make sure reclaim level is low (below 6’)
	- On SCADA under filters tab, valves. Select the filter to be backwashed from right side choices. Click “Initiate backwash” on top right side. 
	- With hose spray down exposed surfaces of tank (walls, pipes and ledges)  
	<br /> 


- <u>Manual filter backwash</u>
	- Operations control computer:
		- Make sure reclaim level is low (below 6’)
		- Start reclaim pump, in SCADA change the lead pump start level to below current level and once pump starts return the start value to its previous level. 
		- On SCADA go into filters, under filter control record “runtime since wash” for filter to be backwashed.

	- Filter control console:
		1. At filter control console switch filter into “Local control” (bottom right switch)
		2. Close “Settled water filter influent valve” (top second button in from left)
		3. Open “Filter drain valve” (top second button in from right) allow filter to drain

	- Individual cell:
		1. Open “Right cell sand wash valve” (top right button)
		2. With hose spray down exposed surfaces of tank (walls, pipes and ledges)
		3. Close “Right cell sand wash valve” after a few minutes 
		4. Open “Left cell sand wash valve” (top left button)
		5. With hose spray down exposed surfaces of tank (walls, pipes and ledges)
		6. Close “Left cell sand wash valve” after a few minutes 	
		7. Open “Right cell backwash valve” (far right knob) slowly, once it starts to open go to next step
		8. Start Wash water pump” (middle bottom button) 
		9. Open ‘Right cell backwash valve” slowly with pauses until you reach approximately 60% open, around 7.5 MGD (BKW FM, listed on the bottom middle of the backwash control screen)
		10. Open “Right cell sand wash valve” allow to run for a few minutes and close
		11. Once the water is clear slowly close “Right side backwash valve” (see next step) should take approximately 35,000 gallons to wash each side (Right K gallons on backwash control screen)
		12. Slowly Open “Left cell backwash valve” as “Right cell backwash valve” is closing. (If Left side does not start to open before right side closes stop wash water pump and see special notes below)
		13. Repeat Individual cell steps 7-11 for unwashed side stopping wash water pump before “Left cell backwash valve” fully closes

	- After backwash:
		1. Close “Filter drain valve” (Top button 2 in from right)
		2-Open “Settled water filter influent valve” (Top button 2 in from left), make sure basin level does not fall below 10.5’, close “Settled water filter influent valve” if it approaches 10.5’ and wait for basin to recover before continuing to fill
		3. Close “Settled water filter influent valve,” all valves should be closed and have red lights on
		4. At SCADA computer screen make sure filter is “out of service”
		5. At filter control console switch filter to “Remote control” (Bottom right switch), “settled water filter influent valve” should open 
		6. Record run hours and water used in backwash 
		7. Enter data into filter work sheet 
			- Run hours and Max head loss are found on SCADA under the filters tab, Filter control
			- Max Turbidity is found on SCADA under the filters tab, Turbidity
			- Select each filter and run point parameter, 24 hour trend and find the max
		8. Clear run hours in SCADA, (Filters, filter setpoint, runs (bottom right), click “manual wash” for filter hours to be cleared
***

### Special Notes
-If right cell or left cell backwash valves will not close you can manually close them downstairs under the filters by opening the petcock on the valve. 

-If backwash pumps will not shut down you can manually turn them off at the circuit breakers in the motor room, backwash #2 is on the north panel and backwash #1 is on the south panel. 
***
