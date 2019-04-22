______________Scatter Documentation and Readme______________
developed and designed by rpg.aleksy

___________________________Description___________________________

Scatter is similar to the Random device native to Ableton with the difference,
that it does not randomize incoming notes but rather Parameters within Ableton Live,
which you can freely choose.

___________________________Function______________________________

- By turning the "Minimum" and "Maximum" knobs you select the range of values that Scatter
	will send out to mapped parameters.
- Turning the "Chance" knob you specify what the chances are of parameters being randomized.

	EXAMPLES
		- Minimum 40%, Chance 100%, Maximum 95%
			Mapped parameters will be set to a value between 40% and 95%
			for every incoming MIDI note.

		- Minimum 0%, Chance 25%, Maximum 50%
			Mapped parameters have a 25% chance of getting changed to a value
			between 0 and 50% for every incoming MIDI note.

		- Minimum 60%, Chance 0%, Maximum 75%
			Mapped parameters will not change.


- MIDI Mode specifies whether or not incoming MIDI notes will pass through the device or not.
	Switch between modes by clicking the blue text saying either "Bypass" or "Through".
	"Bypass" will 'eat' incoming MIDI notes, while "Through" will let notes through,
	allowing you to place more devices and after Scatter.


- The "Show Mappers" buttons lets you see all 8 Mappers and their state.
	To MAP a parameter, first press a Map Button of your choice so that its color changes.
		Continue by clicking on the desired Parameter within Ableton Live.
		The Map buttons name should change to the parameters name that was mapped.
	To UNMAP a parameter from a Map button, press the circular "X" button
		next to the button you want to unmap.
	The "Solo" buttons next to the array of Map Buttons specify whether the mapped
		parameters next to them will receive an individually generated random value.

	EXAMPLE
		- Minimum 30%, Chance 100%, Maximum 60%
		- Map Button 1: Left Delay, Solo activated
		- Map Button 2: Reverb Decay, Solo deactivated
		- Map Button 3: Gain, Solo deactivated
			Incoming MIDI notes will cause "Reverb Decay" and "Gain"
			to be set to the same value between 30% and 60%, while "Left Delay"
			will be set to a seperate value within the same range.

_________________________________________________________________