# Demonstration

## Synthesizer Module
Initial experimentation
Tried using the [Synthesizer Python library](https://pypi.org/project/synthesizer/)
Disadvantages - ony able to play tones at a set interval

<figure class="video_container">
  <video controls="true" allowfullscreen="true" width="500">
    <source src="assets/videos/attempt_1.mp4" type="video/mp4">
  </video>
</figure>

## PyAudio


In searching for another option I found [18alantom](https://github.com/18alantom/synth)'s work on 
making a synth in Python. This used generator functions
> These generator functions use an equation. Each time the next() method is called it returns the
next value in the series. Sound can be generated with a wave 

![Attribution](/assets/images/alan_attribution.png ':size=300')

<figure class="video_container">
  <video controls="true" allowfullscreen="true" width="500">
    <source src="assets/videos/star_wars.mp4" type="video/mp4">
  </video>
</figure>

## Alternate Wave Oscillators

Order of waveforms demonstrated

1. Sine Wave
2. Square Wave
3. Sawtooth Wave
4. Triangle Wave

<figure class="video_container">
  <video controls="true" allowfullscreen="true" width="500">
    <source src="assets/videos/waveforms.mp4" type="video/mp4">
  </video>
</figure>