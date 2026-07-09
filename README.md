# Gain-Reduction-Toolkit
Implementation of classic audio gain reduction tools: compressor, limiter, clipper, and multiband compressor, following the block diagrams and equations in Zölzer's DAFX: Digital Audio Effects (2nd ed.). 

"[Compression] allows the increase of the overall loudness of the track. Considering that the casual listener often gives preference to the louder of two musical works, a trend has developed towards always higher average levels. Moderation is, however, necessary because the “loudness war” can induce severe degradations of the audio and musical quality [Kat07, Lun07]." -- DAFX

## Overview

Herein can be found implementation of different gain reduction tools often used in audio applications such as engineering, mixing and mastering. 

As expressed in the above quote, these processes often introduce degradation. The quest to have musical outputs be as loud as possible has made for distortion to be commonplace. Some tools exist already to correct these degradations, thus additional steps which allow for analysis and correction of these are included.

Each different tool is presented and explained step by step, as well as combined into a single workflow. Following, a tool for analysis of outputs' quality is offered, to compare their spectrums against that of the original signal. A difference spectrogram is then generated between original and processed spectrum as well as a time-domain null test (output_signal - x), before using this information to correct the degraded outputs.

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
