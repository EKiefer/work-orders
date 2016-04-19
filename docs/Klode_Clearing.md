###Introduction
The Klode raw water intake is an elevated intake located on the bottom of Lake Michigan approximately 4000’ feet out from the Klode pumping station. The intake is composed of 3 rings covered by a grating to prevent large objects from entering the raw water intake line. The intake line connects Lake Michigan to the raw wet well which is filled by gravity equalizing the pressure between the Lake and wet well. 

The intake can become clogged resulting in a reduced water flow and subsequent wet well draw down. This can happen for several reasons including the formation of frazil ice blockages. Frazil ice forms when surface water loses heat rapidly and becomes super cooled. Turbulence then mixes the water and small ice crystals (frazil ice) form and are drawn down in the water column, due to its small size it is ineffectively buoyant compared to the turbulent forces. The ice crystal then increase in size due to the contact with super cooled water and can adhere to structures in the water. The frazil will adhere to the grating on the intake and increase in size starting to cause a blockage resulting in a pressure difference between the 2 sides of the grating and allows the blockage to grow. 
***

###Operational Warnings
The reduction in raw water flow to the settling basins will eventually reduce the channel level and stop the filters from filtering. The clear well level will drop and the low lift pumps will not supply enough water to the UV and it will shut down. If the blockage is not cleared eventually the reservoir will be pumped dry and communities will not have water. This could in turn lead to pipes freezing and breaking due to low pressure and standing water.
***

###Personal Safety
No safety equipment needed if blockage can be cleared by adjusting pumping.
***

###Materials, Supplies & Equipment
None if blockage can be cleared by adjusting pumping. 
***

###Standard Operating Procedure
- If possible try and fill clear well as much as possible
	- Start the reclaim basin pump if needed
- Manually set the clear well pump to 58%, any lower and the UV will stop
-	Set filters to manually filter at .5 mgd, so filters don’t stop
	- If channel level is low you may want to turn some filters off, every filter that is completely stopped must then be backwashed. 
- Turn the raw pump to 67%
- Manually turn off Klode pumps 2 and 4
	- Switches on the wall next to the alarm pad
	- Allow the pump to completely stop
- Control inhibit all 3 options on raw pump 4
	- On the Klode screen on SCADE above where is says RAW 4 right click and select “Toggle Closed CI,” “Toggle Open CI,” “Toggle REQD DO CI”
- Wait for  the wet well to fill and stabilize
- Open valve to allow water in pump line to fill wet well and flush out intake
	- Select “Toggle REQD DO VALUE”
	- Wait until wet well fills and flushes out returning to previous level
- Close valve
	- Select “TOGGLE REQD DO VALUE”
- Clear fault for pump 4 
	- Click on pump to bring up screen and select clear fault
- Turn off the 3 control inhibits
- Manually turn pumps 2 and 4 back on in auto, switches on the wall
	- May take up to 2 minutes for the pump to actually start pumping while the air in the line is cleared
- Leave pump running at 67% and check if wet well maintains level
	- If wet well maintains level 
		- Turn raw pump back up to original level
		- If channel level is above 10.5’ turn filters back to auto
	- If the wet well level drops again repeat all steps and try to clear blockage. 
- Turn the clear well pump back to auto


### Special Notes
When waiting for the raw pump to start up if it takes to long an alarm for polymer feed pump may go off. Watch to see when the pump starts pumping water and when flow gets up around 1 MGD the polymer pump should automatically restart. 
***
