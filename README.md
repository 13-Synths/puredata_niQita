# pd_niQita
niQita - Monophonic Sequencer for Pure Data

niQita is a monophonic MIDI sequencer for Pure Data, designed particularly for basslines and rhythmic hooks. Think of it like a guided MIDI missile that allows for nuanced and expressive performance of a MIDI instrument.

It takes inspiration (and features) from two existing hardware sequencers - namely, the Intellijel Metropolis (the eurorack adaptation of the famed M185 sequencer from the Roland System 100m), and the Elektron line of products, such as the Digitakt and Model:Samples.

niQita is designed to allow for the creation of MIDI patterns that aren't as "steppy" as most step sequencers. This is achieved by allowing you to define the duration of each step, as well as one of several types of triggers for that step - namely, a single short note, a single held note, or a repeated note which is triggered at a rate determined by a subdivision of the trigger duration (e.g. 2 pulses over the course of 4 sixteenth notes, etc).

Also, per-step "parameter locks" for the modwheel (CC1) and two other CC controls (definable) are included, to allow the control of instrument parameters in an expressive way - i.e. per-step values for controls such as filter cutoff, envelope release, etc. This helps bring sequences to life and make them speak.

The sequencer allows for 16 steps per sequence, and can store a total of 256 patterns (grouped into 16 banks of 16 patterns) into memory.
