# Fingerprint Enhancement and Minutiae Extraction Analysis

This project performs a comparative analysis of fingerprint enhancement methods using the IIITD fingerprint dataset.

## Objective

The work evaluates the impact of different fingerprint enhancement techniques on minutiae extraction and matching performance.

## Enhancement Methods Compared

1. Original Fingerprints (Step-1 only)
2. Hong Method (Gabor Filtering)
3. STFT (Short-Time Fourier Transform) Enhancement
4. ODF (Orientation Diffusion Filtering)

## Experimental Setup

Two minutiae extraction scenarios are evaluated:

1. Full fingerprint area
2. High-reliability region only

For each enhancement method, the following are analyzed:

- Average number of minutiae extracted
- Matching performance
- EER (Equal Error Rate)
- FMR @ FNMR = 0.01

## Expected Outcome

The project aims to produce a comparative performance assessment paper analyzing the effectiveness of different enhancement techniques for fingerprint recognition.

## Dataset

- IIITD Fingerprint Dataset

## Basic Steps Followed
1. Preprocessing : Segmentation -> YOLO-based, video followed : https://www.youtube.com/watch?v=r0RspiLG260
2. Three Approaches Applied
3. Postprocessing
   
## References

- Hong et al. fingerprint enhancement using Gabor filtering
- STFT-based fingerprint enhancement paper
- Orientation Diffusion Filtering (ODF) paper
