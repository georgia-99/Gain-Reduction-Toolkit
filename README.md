# Gain-Reduction-Toolkit
Implementation of classic audio gain reduction tools: compressor, limiter, clipper, and multiband compressor, following the block diagrams and equations in Zölzer's DAFX: Digital Audio Effects (2nd ed.). 

"[Compression] allows the increase of the overall loudness of the track. Considering that the casual listener often gives preference to the louder of two musical works, a trend has developed towards always higher average levels. Moderation is, however, necessary because the “loudness war” can induce severe degradations of the audio and musical quality [Kat07, Lun07]." -- DAFX

## Overview

Herein can be found implementation of different gain reduction tools often used in audio applications such as recording, editing, mixing and mastering. 

As expressed in the above quote, these processes often introduce quality degradation. The quest to have musical outputs be as loud as possible has made for distortion to be commonplace. Some tools exist already to correct these degradations; additional steps which allow for analysis and correction of these are included in the toolkit.

Each different tool is presented and explained step by step, as well as combined into a single workflow. Following, a tool for analysis of outputs' quality is offered, to compare their spectrums against that of the original signal. A difference spectrogram is then generated between original and processed spectrum as well as a time-domain null test (output_signal - x), before using this information to correct the degraded outputs.

The goal of this project is to provide an educational tool for those who want to learn exactly how gain-reduction plugins work, while also exploring ways to improve them by addressing how gain reduction can degrade audio quality.

## README Contents
1. Step-by-step workflow for each tool
   - Standard compressor 
   - Limiter 
   - Clipper 
   - Multiband compressor 
2. Tool implementations, output analysis
3. Corrective techniques, improvements
4. Description of user implementation)
5. References

## Repository contents

standard compressor
limiter
clipper
multiband compressor
combined gain reduction, analysis and correction


