# ESP32_MIDI_ParaphonicSplitter
 MIDI Splitter that passes multiple keys out to separate MIDI Channels

 Developed to split a MIDI stream from a MIDI keyboard into three channels. The goal being allowing paraphonic playing of single voiced analog synths. For instance, take three Behringer Model Ds, link them up, polyphonic 'Moog'.
 
 Will this work? I'm not sure, but it's a fun thing to try.

 Here's how it should work:

 Listen to the flow of MIDI In
 Take the first key, send it to MIDI channel 1
 Take the Second pressed key, send it to MIDI channel 2
