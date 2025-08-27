---
layout: page
title: Automatic drum transcription
description:
img: /assets/img/drum.jpg
importance: 1
category: work
---

Automatic Drum Transcription (ADT) describes the process of transcribing audio files containing drum sounds into a musical representation indicating the onsets of each drum sound in the recording.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/drum.jpg' | relative_url }}" alt="" title="keersmaeker"/>
    </div>
</div>
<div class="caption">
photo: John Seb Barber
</div>

This project is carried out in collaboration with <a href="https://drumstik.com" target=blank>Drumstik</a>, and aims at producing automatically a musical score from a real-time audio recording.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/drumstik.jpg' | relative_url }}" alt="" title="keersmaeker"/>
    </div>
</div>
<div class="caption">
Drumstik application used with an electronic drum kit
</div>

For this application, I use a deep learning approach. This model compute a probability at all times that is use to know if some parts of the drum (snare, bass, hi-hat, etc.) are played.
