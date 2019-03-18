# Exercise for Chapter 2 and 3


## Implement Goertzel Algorithm

Read [this description](https://www.embedded.com/design/configurable-systems/4024443/The-Goertzel-Algorithm) of the Algorithm.

### Exercise 1 - Read a binary file into a list


There are two example sound files. They contain *DTMF* signals.
The sound is encoded as signed 8/16 bit PCM mono audio at 44100 Hz, without any header.

Read the 8-bit file using Data.ByteString readFile.

### Exercise 2 - Implement Goertzel with sequential code

Implement a routine that can detect a given frequency.
Invoke the the algorithm to detect different frequencies:

* 697 Hz
* 852 Hz
* 1209 Hz
* 1477 Hz

These are part of the [DTMF table](https://en.wikipedia.org/wiki/Dual-tone_multi-frequency_signaling).

### Exercise 3 - Split the work into chunks and use rpar and rseq 

The Goertzel Algorithm relys on chunks. 
