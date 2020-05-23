# Introduction

This PCB replaces the RF modulatorbox on a Sinclair ZX Spectrum computer. It's main purpose is to improve the video output of the ZX Spectrum by seperating the luma/sync (Y) and chroma (C) signals.

The ZX Spectrum does have a composite signal that goes into the modulatorbox, a simple modification is to cut off the +5 volt to the modulator, disconnect the composite signal from the modulator and feed this signal to the RCA jack of the modulator. This results in a signal that is slightly better than RF. This is a common mod and is easy to perform. However, the image has a lot of dot crawl, because the pixel clock is not synchronised with the PAL colour subcarrier.

# Composite output works, why designing this board?
Why not? I wanted some exercise in KiCad and I am using a RetroTink 2X. The Spectrum's composite output is absolutely horrible on this. However, it accepts s-video signal. So, that made me wonder, is it possible to seperate the Y/C signals on a ZX Spectrum? Some googling later I found this thread on the World of Spectrum forums: https://www.worldofspectrum.org/forums/discussion/47120/new-video-about-s-video-modification-on-issue-two-48k-spectrum/p1. Credits to 1024MAK and RGA24.

I first built it up on a piece of stripboard and did some testing and it worked quite good with my RetroTink. Nice clear image without dot crawl. So, to answer the question above, I designed this to make it easier to build and reversible. 

# The Board









