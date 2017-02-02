# enigma-logisim
!CAUTION! Poor english...

I started this project for school (exacly for a lab-exam at univ.), it's an emulator of the Enigma machine.
I'm not totally sure that the circuit reflects the principle of operation of the real machine.
The wires inside rotors (3 rotors) are mixed randomly, not respects the real rotors that were really used at that time, and there's no plugboard at the moment. It's only a prototype. 

At the bottom i put a gif to explain how to use it, easy: choose a combination (00000 for A... 11001 for Z, and the others six are ignored), click W (write comb.) and let's start to encrypt a message, char-per-char. Then, click again on W and put char-per-char the encrypted string of chars and the clear message will appear.

At the time there's one main PROBLEM that i will fix soon as possible: 
the circuit can't start with the combination of rotors 00000, 00000, 00000. All the 3 rotors must start from a value != 0.

Feel free to contact me for errors:
freeknowLDG@protonmail.com

![alt tag](https://github.com/freeknowLDG/enigma-logisim/blob/master/enigma.gif)
