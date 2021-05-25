# Maintenance-Tracker-v1.0
Original tracker sheet to be used to log equipment maintenance and job details. Was initially purposed to fill the gap between no standard parts ordering, and third-party parts and equipment database software. 

*Input Sheet
  The input sheet is to be used to input job details and as equipment parts usage entry.
  
Unit Number:
  Unit number selection that any parts selected will be billed to.
  
Date:
  Date of either job starting details or parts usage entry.
  
Crew:
  Selection of which crew (color coded) is performing the job or maintenance.
  
Supervisor:
  Name of the crew supervisor that is performing either the job or maintenance.
  
Customer:
  Name of the customer the job is being performed for.
  
Wellsite Identifier:
  Name of the site that the job or maintenance is being performed on.
  
Average Treating Pressure:
  Input of the average treating pressure (psi) of the job being performed.
  
Sand Volume Per Stage:
  Input of the proppant volume pumped for the stage.
  
Clean Volume Per Stage:
  Input of the clean fluid volume pumped for the stage.
  
Slipstream ?:
  Selection of whether the fluid system is all slurry (water & proppant) or slipstream (water + (water & proppant)).

Stroke Count:
  Input of the stroke count total of the unit being maintained.
  
Unit Condition:
  Selection of the type of fluid the unit is set up to pump (affects component degradation).
  
Fluid End Type:
  Selection of the type of fluid end the unit is equipped with.
  
Carbide, Conventional, or Mixed:
  Selection of the seat type installed on the fluid end.
  
Engine Hours:
  Input for the entry of the unit deck engine hours.
  
Iron Expiration Date:
  Input of the units bridal iron expiration date.
  
Well and Stage Number:
  Input of the well identifier and the stage count.
  
All Valves:
  Click to execute "allvalves" function; outputs the fluid end appropriate type and quantity of valves to the "Valve" cell.
  
All Seats:
  Click to execute "allseats" function; outputs the fluid end appropriate type and quantity of seats to the "Seat" cell.
  
All Packing:
  Click to execute "allpacking" function; outputs the fluid end appropriate type and quantity of packing to the "Packing" cell.
  
Bare Block:
  Click to execute "bareblock" function; outputs the fluid end appropriate type and quantity of valves, seats, and packing to the "Valve", "Seat", and "Packing" cells.
  
New Fluid End:
  Click to execute "newfluidend" function; outputs the fluid end appropriate type and quantity of valves, seats, and packing to the "Valve", "Seat", and "Packing" cells.
  
T#1 - T#5:
  Click individual icons to execute the "valve1inc - valve5inc" or the "seat1inc - seat5inc" functions, representative of the top five valves and seats in the fluid end.
  
B#1 - B#5:
  Click individual icons to execute the "valve6inc - valve10inc" or the "seat6inc - seat10inc" functions, representative of the bottom five valves and seats in the fluid end.
  
P#1 - P#5:
  Click individual icons to execute the "packing1inc - packing5inc" functions, representative of the packing locations #1-#5 in the fluid end.
  
Cancel Icon:
  Click the cancel icon to execute the "clearall" function and clear all previous parts selections on the sheet.
  
Submit:
  Click the submit icon to execute the "submit" function. This will transfer the sheets data to both the "Parts" and "Log" sheets.
  
<img width="689" alt="Input Sheet" src="https://user-images.githubusercontent.com/84663264/119549272-0cdba580-bd65-11eb-9bfd-cc2a5b3125e1.png">

*Scoreboard:
  The Scoreboard sheet is broken down into two parts; the fleet maintenance board on the left-hand side and the unit board on the right.
  The purpose is to give an overview of fleet maintenance as well as being capabale of selecting a specific unit to observe it's indicidual fluid end components usage ratings. 

Position:
  The position indicates the physical position of the unit on the site.
  
Select Condition:
  Selection options to indicate what type of fluid system the unit is pumping. This will affect the calculations for wear and tear on the units fluid end components.
  
Select Unit Number:
  Selection to identify the unit number.
  
Seat Type:
  Selection of type of seats installed in the fluid end.
  
Current Pump Strokes:
  Input of the units current stroke count.
  
Strokes at Last Valve Change:
  Input of the units stroke count at the last time the fluid end valves were inspected or replaced.
  
Strokes at Last Seat Change:
  Input of the units stroke count at the last time the fluid end seats were inspected or replaced.
  
Strokes at Last Packing Change:
  Input of the units stroke count at the last time the fluid end packings were inspected or replaced.
  
Valves:
  Output of the difference between the "Current Pump Strokes" and "Strokes at Last Valve Change" shown as a percentage, indicating percentage of valve wear.
  
Seats:
  Output of the difference between the "Current Pump Strokes" and "Strokes at Last Seat Change" shown as a percentage, indicating percentage of seat wear.
  
Packing:
  Output of the difference between the "Current Pump Strokes" and "Strokes at Last Packing Change" shown as a percentage, indicating percentage of packing wear.
  
Unit Number:
  Selection to select a specific unit; this will populate the fluid end information from the most recent log entry.
  
Current Strokes:
  Output of the stroke count from the most recent log entry.
  
Current Deck Engine Hours:
  Output of the deck engine hours from the most recent log entry.
  
Iron Expiration Date:
  Output of the unit bridal iron expiration date from the most recent log entry.
  
Clean or Dirty:
  Selection of the fluid system the unit is currently pumping (affects calculation for fluid end parts degradation).
  
Fluid End Type:
  Output of the unit fluid end type fromt the most recent log entry.
  
<img width="745" alt="Scoreboard" src="https://user-images.githubusercontent.com/84663264/119367904-6e761400-bc80-11eb-9581-0c6242e83d0e.png">

*Parts Sheet:
  The parts sheet receives input from the "Input" sheet. This is purposed for the Parts department to identify unit parts usage for replenishment.
  
Date:
  Output of the date from the "Input" page.
  
Well/Stage #:
  Output of the well identifier and stage number from the "Input" page.
  
Unit #:
  Output of the unit number from the "Input" page.
  
Supervisor:
  Output of the name of the supervisor from the "Input" page.
  
Fluid End Type:
  Output of the fluid end type from the "Input" page.
  
Valves:
  Output of the quantity of valves used from the "Input" page.
  
Conventional Seats:
  Output of the quantity of the conventional seats used from the "Input" page.
  
Carbide Seats:
  Output of the quantity of the carbide seats used from the "Input" page.
  
Serial Number:
  Output of the searial number for carbide seats used from the "Input" page.
  



<img width="853" alt="Parts Sheet" src="https://user-images.githubusercontent.com/84663264/119367925-73d35e80-bc80-11eb-82ad-e55244066d83.png">
<img width="618" alt="Log Sheet" src="https://user-images.githubusercontent.com/84663264/119367940-7635b880-bc80-11eb-8a95-770023ede602.png">
<img width="636" alt="Search Sheet" src="https://user-images.githubusercontent.com/84663264/119367950-77ff7c00-bc80-11eb-947a-a6ed125b1835.png">

