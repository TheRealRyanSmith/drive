# Drive

## Sections

01 Map / Search Mode
02 Driving Mode




## Architect Outline

* 01.01 Map/Search View - Map Active

	- map
	- search field
	- tap into the search field
	- drop a pin on the map
	- contextual layer with name of destination, distance, and start button (goes to driving mode)
	- locate me button (center on my current location)
  


* 01.02 Map/Search View - Search Active

*If user has tapped into the search field.*

	- search field
	- clear search field button
	- keyboard
	- show a list of type ahead results (location, distance from current location)
	- tap a result to see that destination on a map



* 02.00 Driving Mode Global Elements

*Same for all Driving Mode views.*

	- label with estimated arrival time
	- interaction swipe to switch pages
	- page dot indicators
	- close button



* 02.01 Driving Mode To

	- label with destination
	- label with estimated hours : mins until arrival
	- label with miles to go
	- label with average speed
	- global labels, controls as defined above



* 02.02 Driving Mode From

	- label with starting city, state
	- label with estimated hours : mins since tracking started
	- label with miles elapsed since tracking started
	- label with average speed
	- global labels, controls as defined above



* 02.03 Driving Mode Averages

	- label with average speed last 15 minutes
	- label with average speed last hour
	- label with average speed since tracking started
	- global labels, controls as defined above

