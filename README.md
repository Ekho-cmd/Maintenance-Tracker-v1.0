# Maintenance-Tracker-v1.0
Original tracker sheet to be used to log equipment maintenance and job details. Was initially purposed to fill the gap between email parts ordering, and third-party parts and equipment database software. 

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
  The Scoreboard sheet is broken down into two parts; the fleet maintenance board on the left-hand side and the unit board on the right-hand side.
  The purpose is to give an overview of fleet maintenance, as well as being capabale of selecting a specific unit to observe the individual fluid end components usage. 

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
  
Spring:
  Output of the quantity of springs used from the "Input" page.
  
D-Ring:
  Output of the quantity of D-Rings used from the "Input" page.
  
Discharge Cover:
  Output of the quantity of discharge covers used from the "Input" page.
  
Suction Cover:
  Output of the quantity of suction covers used from the "Input" page.
  
Discharge Retaining Nut:
  Output of the quantity of discharge retaining nuts used from the "Input" page.
  
Suction Retaining Nut:
  Output of the quantity of suction retaining nuts used from the "Input" page.
  
Packing:
  Output of the quantity of packings used from the "Input" page.
  
Packing Nut:
  Output of the quantity of packing nuts used from the "Input" page.
  
Plunger:
  Output of the quantity of plungers used from the "Input" page.
  
Pony Rod Clamp:
  Output of the quantity of pony rod clamps used from the "Input" page.
  
Stuffing Box:
  Output of the quantity of stuffing boxes used from the "Input" page.
  
Stuffing Box Seal:
  Output of the quantity of stuffing box seals used from the "Input" page.
  
Stuffing Box Bolt:
  Output of the quantity of stuffing box bolts used from the "Input" page.
  
Stuffing Box Sleeve:
  Output of the quantity of stuffing box sleeves used from the "Input" page.
  
Face Seal:
  Output of the quantity of face seals used fromt the "Input" page.
  
Spring Boot:
  Output of the quantity of spring boots used from the "Input" page.
  
Valve Guide:
  Output of the quantity of valve guides used from the "Input" page.
  
*Field Mechanic Use:
  Area of sheet purposed for parts ordering by the onsite maintenance technicians.
  
Hours:
  Input the unit engine hours.
  
Strokes:
  Input the unit pony rod strokes.
  
Mechanic:
  Input the name of the maintenance technician.
  
*Replensishment (Parts Department Use Only):
  Area of sheet purposed for the Parts Department to input parts that have been billed for field delivery.
  
Date:
  Input of the date parts have been billed.
  
Quantity:
  Input of the quantity of parts that have been billed.
  
Notes:
  Input for Parts Department comments.
  
*Driver & Unit #:
  Area of sheet purposed for the use of the Dispatch Department identifying the driver name and unit number that is scheduled to deliver the parts to the field.
  
Name & Unit #:
  Input of the driver name and the unit number they will be driving.
  
*Parts Recieved:
  Area of sheet purposed for the onsite supervisor to verify the delivery of parts to the field.
  
Supervisor:
  Input of the onsite supervisors name.

<img width="853" alt="Parts Sheet" src="https://user-images.githubusercontent.com/84663264/119367925-73d35e80-bc80-11eb-82ad-e55244066d83.png">

*Log:
  The Log sheet is purposed to record the data input from the "Input" sheet, and is used as a relational database for retrieving data with the "Scoreboard", "Parts", and "Search" sheets.
  
Unit #'s:
  Output of the unit number from the "Input" page.
  
Date:
  Output of the date from the "Input" page.
  
Crew:
  Output of the crew name from the "Input" page.
  
Supervisor:
  Output of the supervisor name from the "Input" page.
  
Customer:
  Output of the customer name from the "Input" page.
  
Wellsite Identifier:
  Output of the wellsite identifier from the "Input" page.
  
Average Treating Pressure psi:
  Output of the average treating pressure recorded in psi, from the "Input" page.
  
Stoke Count (Million):
  Output of the unit stroke count recorded as n x E3, from the "Input" page.
  
Engine Hours:
  Output of the unit engine hours from the "Input" page.
  
Iron Expiration Date:
  Output of the iron expiration date from the "Input" page.
  
Total Sand Volume Per Stage:
  Output of the total proppant volume pumped for the stage from the "Input" page.
  
Total Clean Volume Per Stage (bbl):
  Output of the total clean fluid volume recorded as barrels per minute (bpm), from the "Input" page.
  
Slipstream (Y/N):
  Output of the slipstream selection from the "Input" page.
  
Dirty of Clean:
  Output of the dirty or clean selection from the "Input" page.
  
(# Valves Changed):
  Output of the quantity of valves replaced from the "Input" page.
  
(# Seats Changed):
  Output of the quantity of seats replaced from the "Input" page.
  
Seat Type (Carbide or Conventional):
  Output of the selection of seat type from the "Input" page.
  
(# Packing Replaced):
  Output of the quantity of packing replaced from the "Input" page.
  
Fluid End Type:
  Output of the selection of fluid end type from the "Input" page.
  
NOTES:
  Output of comments put in the notes section from the "Input" page.
  
ValveT1 - ValveT5:
  Output of the top valves replaced in the unit fluid end from the "Input" page.
  
ValveB1 - ValveB5:
  Output of the bottom valves replaced in the unit fluid end from the "Input" page.
  
CarbT1 - CarbT5:
  Output of the top carbide seats replaced in the unit fluid end from the "Input" page.
  
CarbB1 - CarbB5:
  Output of the bottom carbide seats replaced in the unit fluid end from the "Input" page.
  
ConvT1 - ConvT5:
  Output of the top conventional seats replaced in the unit fluid end from the "Input" page.
  
ConvB1 - ConvB5:
  Output of the bottom conventional seats replaced in the unit fluid end from the "Input" page.
  
Packing1 - Packing5:
  Output of the packing replaced in the unit fluid end from the "Input" page.
  
Minimum Valve Strokes:
  Output of the furthest stroke count the valves were replaced from the "Input" page.
  
Minimum Seat Strokes:
  Output of the furthest stroke count the seats were replaced from the "Input" page.
  
Minimum Packing Strokes:
  Output of the furthest stroke count the packings were replaced from the "Input" page.
  
Strokes at Last Valve Change:
  Output of the most recent stroke count the valves were replaced from the "Input" page.
  
Strokes at Last Carb Seat Change:
  Output of the most recent stroke count the carbide seats were replaced from the "Input" page.
  
Strokes at Last Packing Change:
  Output of the most recent stroke count the packings were replaced from the "Input" page.

<img width="618" alt="Log Sheet" src="https://user-images.githubusercontent.com/84663264/119367940-7635b880-bc80-11eb-8a95-770023ede602.png">

*Search:
  The search sheet is purposed as a tool to search maintenance records by unit number.
  
Select Unit Number From Dropdown:
  Drop down selection used to select unit number.
  
Crew:
  Output of the crew name from the "Log" page.
  
Supervisor:
  Output of the supervisor name from the "Log" page.
  
Customer:
  Output of the customer name from the "Log" page.
  
Wellsite Identifier:
  Output of the wellsite identifier from the "Log" page.
  
Average Treating Pressure psi:
  Output of the average treating pressure recorded in pounds per square inch (psi), from the "Log" page.
  
Stroke Count (Million):
  Output of the stroke count recorded as n x E3 from the "Log" page.
  
Engine Hours:
  Output of the unit engine hours from the "Log" page.
  
Iron Expiration Date:
  Output of the iron expiration date from the "Log" page.
  
Total Sand Volume Per Stage:
  Output of the total proppant volume recorded in pounds used for the stage, from the "Log" page.
  
Total Clean Volume Per Stage:
  Output of the total clean fluid volume recorded in barrels per minute (bpm), from the "Log" page.
  
Slipstream (Y or N):
  Output of the slipstream selection from the "Log" page.
  
Dirty of Clean:
  Output of the dirty or clean selection from the "Log" page.
  
(# Valves Changed):
  Output of the quantity of valves used from the "Log" page.
  
(# Seats Changed):
  Output of the quantity of seats used from the "Log" page.
  
Seat Type (Carbide or Conventional):
  Output of the selection of seat type from the "Log" page.
  
(# Packing Replaced):
  Output of the quantity of packing replaced in the unit fluid end from the "Log" page.
  
Fluid End Type:
  Output of the unit fluid end type from the "Log" page.
  
Notes:
  Output of the notes from the "Log" page.
   
ValveT1 - ValveT5:
  Output of the top valves replaced in the unit fluid end from the "Log" page.
  
ValveB1 - ValveB5:
  Output of the bottom valves replaced in the unit fluid end from the "Log" page.
  
CarbT1 - CarbT5:
  Output of the top carbide seats replaced in the unit fluid end from the "Log" page.
  
CarbB1 - CarbB5:
  Output of the bottom carbide seats replaced in the unit fluid end from the "Log" page.
  
ConvT1 - ConvT5:
  Output of the top conventional seats replaced in the unit fluid end from the "Log" page.
  
ConvB1 - ConvB5:
  Output of the bottom conventional seats replaced in the unit fluid end from the "Log" page.
  
Packing1 - Packing5:
  Output of the packings replaced in the unit fluid end from the "Log" page.
  
<img width="636" alt="Search Sheet" src="https://user-images.githubusercontent.com/84663264/119367950-77ff7c00-bc80-11eb-947a-a6ed125b1835.png">






















