# Masking and Inpainting

_A two-stage speech enhancement approach for low SNR and non-stationary noise._

Submited to ICASSP 2020.

## Abstract

Currently, low signal-to-noise ratio (SNR) and non-stationary noise cause severe performance degradation for most of speech enhancement models. For better speech enhancement at the above scenarios, this paper proposes a two-stage approach that consists of binary masking and spectrogram inpainting. In the binary masking stage, we first obtain binary mask by hardening soft mask and then use it to remove time-frequency points that are dominated by severe noise. In the spectrogram inpainting stage, we use a CNN with partial convolution to perform inpainting on the masked spectrogram from the previous stage. We compared our approach with two powerful baselines, including Wave-U-Net and CRN, on a low SNR dataset containing lots of non-stationary noises. The experimental results show that our approach outperformed the baselines and achieved the state-of-the-art performance.

## Demo

![Demo Page](/static/demo_page.png)

This [link](http://49.233.87.147:8000/demos/masking-and-inpainting/) gives you access to the Demo page.
The Demo page contains a lot of wav files, please be patient and wait for the loading to complete.