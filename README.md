# Gain-Reduction-Toolkit
Implementation of classic audio gain reduction tools: compressor, limiter, clipper, and multiband compressor, following the block diagrams and equations in Zölzer's DAFX: Digital Audio Effects (2nd ed.). 

"[Compression] allows the increase of the overall loudness of the track. Considering that the casual listener often gives preference to the louder of two musical works, a trend has developed towards always higher average levels. Moderation is, however, necessary because the “loudness war” can induce severe degradations of the audio and musical quality [Kat07, Lun07]." -- DAFX

## Overview

Herein can be found implementation of different gain reduction tools often used in audio applications such as engineering, mixing and mastering. which, as expressed in the above quote, often introduce degradation. The quest to have outputs be as loud as possible has made for a musical landscape filled with distortion. Some tools exist to correct these degradations, which is what inspired this project.

Here, different GR tools are established and explained step by step, before combining them into a single implementation. Then, analysis of the outputs is carried out, to compare their spectrums against that of the original signal. A difference spectrogram is then generated between original and processed spectrum as well as a time-domain null test (output_signal - x), before using this information to correct the degraded outputs.

## Table of Contents
A Step-by-step implementation of different tools

1. Standard compressor implementation
2. Limiter implementation
3. Clipper implementation
4. Multiband compressor implementation

B Combined implementation

C Comparison of outputs

D Suggestion of correction

E Pipeline all together (user implementation)

F References
