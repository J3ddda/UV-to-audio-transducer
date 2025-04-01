# UV-to-audio-transducer
a device or system that takes in UVA and UVB radiation from the sun and turns it into sound - cool art project

🧪 Step 1: Detect UVA and UVB
You’ll need sensors that can specifically detect UVA (315–400 nm) and UVB (280–315 nm) wavelengths.

✅ Sensors:
GUVA-S12SD – UV light sensor (mainly UVA)

VEML6075 – A digital sensor that can measure both UVA and UVB and separates them in its data output.

These sensors give you analog or digital output values representing UV intensity.

🎛 Step 2: Convert Sensor Data to Sound
Now you need to map UV intensity values to sound properties like pitch, volume, timbre, or rhythm.

🧠 Microcontroller:
Arduino, Raspberry Pi, or Teensy – These will read the UV values and drive audio generation.

🧰 Options for Sound Mapping:
Pitch: Higher UV → higher pitch

Volume: More intense UV → louder sound

Timbre/Texture: Varying between sine/square/triangle waves based on ratio of UVA to UVB

🔊 Step 3: Generate Sound
Here’s how you can make the data audible:

Option A: Arduino + Audio Shield
Teensy + Audio Adapter Board lets you generate complex synthesized sounds.

Pure data or Max/MSP patches (if you're using Raspberry Pi or a laptop)

Option B: MIDI Output
Use UV data to control a MIDI instrument (e.g. synth or DAW)

Can use it to trigger samples or change parameters in real time

⚡ Power Supply:
Battery pack with solar charging could keep the whole thing portable and self-sustaining.

🧠 Bonus Ideas:
Stereo Field: Use two sensors spaced apart and pan sound accordingly

Rhythm: Use spikes in UV (e.g. passing clouds) to trigger percussive elements

Tactile Feedback: Pair it with haptics for an embodied experience

