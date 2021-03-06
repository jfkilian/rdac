# RDAC to WAV Decoding

A collection of C and Go code to decode Roland's old RDAC audio encoding format used in their VS line of recorders. 

This is an initial upload of the code I have found on my old systems. I developed it on and off over the last 16 years. It could probably use a bit more organization :)

All the important bits for decoding RDAC and unscrambling the custom FAT file format are here.

Enjoy!

Randy

In the LIV_mode branch this fork contains a prototype for decoding also file recorded with Roland's LIV mode settings. It basically works, but the decoding patterns need to be reverse engineered.
I stopped further research since there is an official tool available: 
https://rolandus.zendesk.com/hc/en-us/articles/201969009-BR-900-BR-900CD-How-to-use-the-BR-Wav-Converter-Software
This software can also devoce VS-880 LIV / Live mode encoded files.

Jürgen

