# Demo Page for Universal Speech Enhancement

## Introduction

Universal speech enhancement is the task of enhancing speech signals that have been recorded in various conditions and distortions, such as noise, reverberation, clipping, EQ distortion, packet loss, codecs loss, bandwidth loss and other distortions.

## Samples

### 1. Bandwidth limitation and Codec Distortion

<div style="display: flex; justify-content: space-around; text-align: center;">
    <div style="flex: 1; margin: 10px;">
        <h3>Original</h3>
        <img src="images/bwe_codecs_original.png" alt="Original" style="width: 100%; height: auto;">
        <audio controls>
            <source src="audio/bwe_codecs_original.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
    <div style="flex: 1; margin: 10px;">
        <h3>GAN Enhanced</h3>
        <img src="images/bwe_codecs_GAN.png" alt="GAN Enhanced" style="width: 100%; height: auto;">
        <audio controls>
            <source src="audio/bwe_codecs_GAN.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
    <div style="flex: 1; margin: 10px;">
        <h3>Storm Enhanced</h3>
        <img src="images/bwe_codecs_Storm.png" alt="Storm Enhanced" style="width: 100%; height: auto;">
        <audio controls>
            <source src="audio/bwe_codecs_Storm.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </div>
</div>
