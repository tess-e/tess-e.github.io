---
layout: page
title: HTTLJ feat. The Voice
description: Interactive installation, 2024
img: assets/img/blackbox.png
importance: 1
category: new media
---
<p>
HTTLJ feat. The Voice
<br>
<u>Tess Eschebach,</u> Ziwei Li, Lola Obielodan, Tucker Rae-Grant, Helena Williams
<br>
December 2024
<br>
Motorized sliders, laser cut wood, Arduino, Raspberry Pi, 3-D printing, Python code, C++ code, speakers, microphone, monitor, sticky note, printed design
<br>
Duration: 1 minute
</p>

<p>
“HTTLJ feat. The Voice,” is an interactive installation that explores the border between ambient noise and private conversations. Created by Tess Eschebach, Ziwei Li, Lola Obielodan, Tucker Rae-Grant, and Helena Williams, this piece takes the form of a radio broadcast booth for a fictional station, HTTLJ. As “The Voice,” visitors are encouraged by passive-aggressive post-its to speak audibly during their “show.”
</p>
<p>
At the desk, they find speakers, a microphone, and a mixing console with a blinking red “start” button. Once the button is pressed, the interaction session begins. Five out of six motorized sliders on the console move to full volume, and the booth floods with overlapping conversations. As they try to lower the volume by moving the sliders, the system calculates an “isolation” value to determine whether they are trying to listen to a single stream. In order to prevent this isolation, the system forces the altered sliders back to the top. The sixth slider insistently maintains its “off” position.
</p>
<p> 
After 30 seconds, the positions of the sliders invert, and only the sixth channel plays sound. At this point, visitors realize that they were being recorded during their “show,” and their voice, filtered out of the cacophony, plays clearly in the booth. The entire interaction session takes about 1 minute to complete.
</p>
In researching audio privacy, we found that eavesdropping–that is, recording conversations without consent–is distinguished from legal recording in public based on how easy it is to isolate a particular conversation. If many voices from many conversations are captured and it is not possible to follow a single conversation, then the recording is more legal. If one conversation stands out clearly, then it is less legal. In “HTTLJ feat. The Voice,” we played with this spectrum by developing a system that seeks to maintain audio privacy even as the visitor tries to eavesdrop. Meanwhile, they are secretly being recorded themselves and folded into the mix.
</p>
<p>
The final exhibit installation consisted of a physical mixing board, a Blue Snowball iCE condenser microphone, and computer speakers. The mixing board was created with a laser-cut wooden console that housed six Arduino-controlled slider potentiometers with 3D-printed slider caps, and a red LED button. The programming for the physical interactions (Arduino), audio mixing (Pygame in Python), and live audio recording (Pyaudio in Python) was housed on a Raspberry Pi.
</p>
