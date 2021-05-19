# Concepts

## What is Sound
> Sound is a pressure wave created by a vibrating object

![Speaker](/assets/gifs/speaker.gif ':size=200')

We can visualize sound with using waves, such as a **Sine wave**

![Speaker](/assets/gifs/sine.gif ':size=200')



## Using Generator functions to Create waveforms

To generate audio we must send a list of numbers to the speaker. These numbers represent how far forward and backward the speaker should travel to produce the sound.

We can use generator functions in Python to accomplish this.

Imagine we start at 0

![Speaker](/assets/images/0,0.png ':size=200')

Then if we use our generator function to get the next value we would get the next step in the sine wave

![Speaker](/assets/images/0.5.png ':size=200')
![Speaker](/assets/images/1.png ':size=200')

We can store each of the y values in this graph into a list 

The first three steps would look like 

[0, 0.5, 1]

After filling up that list (buffer) it can be sent off to the speaker to generate the tone

## Other Waveforms

The demonstration so far has used the sine wave, but there are many other waveforms. Everything you hear is a complex wave of audio that we understand as sounds. For musical purposes common waveforms are 

- Square Wave
- Triangle Wave
- Sawtooth Wave

![Speaker](/assets/images/allWaves.png ':size=600')