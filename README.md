# JPEG Blocking Under Upscaling: The Seam Keeps Its Contrast and Gains Area

Measured across 12 experiments: a JPEG block seam sits at 1.26–1.30× the surrounding gradient at every scale factor, while its area grows as k². Deblocking after upscaling beat deblocking before it on both PSNR and seam contrast. Blind 8-grid detection worked on 4/4 crops. Sharpening did not selectively amplify the seam — it amplified everything by the same ratio.

**Read it with the tables and the reproduction snippets:** <https://celticgemini001.github.io/upgolab-jpeg-blocking-upscale/>

## About this repo

This repository exists to serve one measured article. Every number in it came from
ffmpeg and numpy run on real files on this machine — the commands are in the page so
you can re-run them and get the same rows. Where the measurement contradicted the
hypothesis, the page says so.

## The tool behind the notes

<https://upgolab.com> — browser-based AI upscaler for photos and short video.

## Index

All the guides are cross-linked from the hub:
<https://celticgemini001.github.io/upgolab-tools/>
