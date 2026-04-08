---
layout: page
title: HTTLJ feat. The Voice
description: Interactive Installation, 2024
img: assets/img/the_voice_2024_still.jpg
importance: 1
category: new media
---
<p>
<u>Tess Eschebach,</u> Ziwei Li, Lola Obielodan, Tucker Rae-Grant, Helena Williams
<br>
(Equal contributions, ordered by last name)
</p>
<p>
<i>Designed for CMSC 33218: Surveillance Aesthetics</i>
<br>
December 2024
</p>
<p>
Motorized sliders, laser cut wood, Arduino, Raspberry Pi, 3-D printing, Python code, C++ code, speakers, microphone, monitor, sticky note, printed design
</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/thevoice_2024_interact.png" title="interaction" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Interaction with HTTLJ.
</div>

<p>
<i>HTTLJ feat. The Voice,</i> is an interactive installation that explores the border between ambient noise and private conversations.
This piece takes the form of a radio broadcast booth for a fictional station, HTTLJ. As “The Voice,” visitors are encouraged to speak during their “show.”
</p>
<p>
As a viewer tries to lower the volume on the soundboard by moving the sliders, the system calculates an “isolation” value to determine whether they are trying to listen to a single stream. In order to prevent this isolation, the system forces the altered sliders back to the top. The sixth slider insistently maintains its “off” position.
</p>
<p> 
After 30 seconds, the positions of the sliders invert. At this point, viewers realize that they were being recorded during their “show,” and their voice, filtered out of the cacophony, plays clearly in the booth. The entire interaction session takes about 1 minute to complete.
</p>

<!---
<div class="col-sm mt-3 mt-md-0">
    {% include video.html path="assets/video/The_voice_2024.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
</div>
<div class="caption">
Special thanks to Helena Williams for editing together this demostration video for our project.
</div>
-->
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/the_voice_inside.png" title="inside the voice" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Inside of the laser cut soundboard.
</div>