# //////////

- grain start: point in buffer from where reading starts.

- grain_spread: rate at which grains are triggered/ delay between each grain (time in ms).

- max_grain_duration: grain duration (time in ms).

- grain_pitch_variation: randomly shifts the pitch by a small amount for each grain

- grain_start_variation: randomly shifts the grain start point by a value in the interval ( -specified amount: +specified amount ) (time in ms).

- reverse_grain: reads the buffer backwards (plays grains in reverse).

# ////////
- wave_spacing_on: toggle to use wave_cycling and wave_spacing.

- wave_cycling: it creates a cycle of grains (each one offset by  wave_spacing amount ), where the number of grains in the cycle is set by the specified amount. 
- wave_spacing: increments the start point of each grain by set amount (time in ms).

# ////////
- grain_panning: adds panning to each grain (for most times it doesn't work properly, I get clicks and pops).

- Assign MIDI modhweel function.
- Filter resonance.
- Delay dry.
- Delay wet.
- Delay feedback.
- Delay time(ms).

- ADSR (release doesn't work; it's just the MIDI note on/off).
