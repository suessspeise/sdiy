# SDIY
This repository contains layouts for proto board adaptions of freely available circuits from [Niklas Rönnberg](http://familjenronnberg.se) (`nor`), [Nonlinearcircuits](nonlinearcircuits.com/) (`nlc`), [Skull&Circuits](skullandcircuits.com/) (`skull`), [David Hailant](https://www.davidhaillant.com/) (`hailant`), [Barton Musical Circuits](http://www.bartonmusicalcircuits.com) (`bmc`), [Ken Stone](http://www.cgs.synth.net/) (`cgs`), [aiynthesis](aisynthesis.com/) (`aisynth`) and myself (`invest`).


### Filter and Resonance
 - `cgs30_bandpass`, bandpass filter with option to stack for multiband filter
 - `nlc_buchlaLPG`, Low pass gate
 - `skull_vcf-1`, vactrol based VCF, works well as a LPG.

### Modulation
 - `nlc_triad`, dual AR envelope 
 - `nlc_sloth-basic`, chaos oscillator LFO
 - `nor_pseudorandom-lfo`, mixed suare waves giving pseudorandom CVs
 - `hailant_lfo-1.4`, basic OpAmp LFO
 - `skull_VCA1`, cheap and simple transistor based VCA
 - `miaw_40106bank`, just 6 unipolar LFO square waves
 - `nlc_jerkoff`, chaotic oscillator LFO

### Sequencing
 - `invest_baby4`, 4 step sequencer + slew limiter
 - `invest_baby8_cv`, cascading 8 step sequencer
 - `nlc_arseq`, 4 step sequencer, each step with attack and release

### Utility
 - `aisynth_matrixmixer`, simple schematics, lots of wiring
 - `nor_clock-divider`, 4024 based clock divider
 - `BMC069_gate2trigger`, gives triggers on rising and falling edge
 - `nor_trigger2gate`, with settable gate length, 555 based
 - `bmc079_risefalldetector`, generates gates, indicating if an incoming singal is rising or falling
 - `invest_555clock-multiple`, multiple with a clock source normaled to the input
 - `skull_attenuvert`, 4 attenueverters
 - `nlc_bools`, logic module, logic type interchangable + stepped sequence and slew limiter
 - `nlc_diffrect`, differential rectifier...
 - `skull_multiple`, dual 1 to 3 multiple with LED

### Waveshaping
 - `nlc_dualneuron`, two neurons in one unit (for the sake of using all OpAmps)
 - `cgs52_wavefolder`, most simple wavefolder, just two transistors

### Sound Source
 - `nor_colourednoise`, white, pink, red and blue noise, based on transistor reverse break down
 - `nlc_ota-vco`, (not working properly)

### Percussion
 - `nlc_vactrol-pill`, 4046+vactrol
 - `nlc_bong0`, twin-T with a LED as nonlinear resistor
 - `miaw_smurfdrum`, passive drum with fart sounds 

### Effects
 - `nlc_nulla_delay`, simple PT2399 delay

### Misc
 - `invest_eurobus`, busboard with cheap 5x7cm proto board
 - `invest_little-speaker`, just a drill guide rackmounting a speaker i found at a flew market
 - `invest_rackdrillguide`, a drill guide for rails from reichelt.de
