Garbage Guru is a smart neighbourhood alert system designed to solve a common local problem: missed garbage collection and scavengers scattering rubbish after collection.

In many neighbourhoods, residents are unaware when the garbage truck is nearby. This leads to bins being put out too late, bags being torn open by scavengers, and streets left dirty. Garbage Guru aims to notify households exactly when the garbage truck is approaching, helping residents put bins out on time and reduce mess, health risks, and frustration.

The Solution

Garbage Guru uses GPS and long-range wireless communication (LoRa) to track the garbage truck in real time and alert nearby households when it is approaching.
	•	A unit on the garbage truck broadcasts its live GPS position
	•	A base station receives and rebroadcasts this data
	•	Household units compare the truck’s position to their own and trigger an alert (buzzer / LED) when the truck is close

This ensures bins are placed outside just in time, reducing scavenger activity and keeping the neighbourhood cleaner.

Main Components
	•	ESP32 microcontrollers
	•	LoRa modules (e.g. T-Beam)
	•	GPS modules
	•	Buzzer / LED indicators
	•	Power supply (battery-based)
