# Structural and Diffusion MRI in Essential Tremor

## Overview

This dataset contains structural MRI and diffusion-weighted MRI acquired from participants with Essential Tremor.

The dataset has been organized according to the Brain Imaging Data Structure (BIDS).

Anatomical images have been defaced prior to public release.

------------------------------------------------

## MRI Sequences

Each participant contains:

• T1-weighted MPRAGE
• T2-FLAIR
• White Matter-Nulled MRI (WMn)
• Diffusion MRI (DWI)

------------------------------------------------

## Scanner

Siemens MAGNETOM Prisma Fit
3 Tesla

------------------------------------------------

## Participant IDs

Participant identifiers have been anonymized.

sub-001
sub-002
...

------------------------------------------------

## Defacing

All anatomical images have been defaced using pydeface.

Diffusion images were not defaced because they do not contain sufficient facial anatomy for reconstruction.

------------------------------------------------

## Notes

WMn images are provided as an additional anatomical contrast and use the acquisition label

acq-wmn

within the BIDS specification.

------------------------------------------------

## Contact

Name: Haden Ray

Institution: UNC Chapel Hill

Email: haden_ray@med.unc.edu