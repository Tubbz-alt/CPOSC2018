# CPOSC 2018: Decoding Weather Satellites

## About

This repository contains information and resources related to
CPOSC 2018 talk: **Decoding Weather Satellites**

Resources include:
- LaTeX template for SDR giveaway package
- LaTeX Beamer files for talk

## Building the Project Files

**Prerequesities:**
- LaTeX (pdflatex preferred)

```
pdflatex pamphlet/sdrguide.tex
pdflatex presentation/cposc2018.tex
```

There should be two PDFs created, one
for the guide included in the SDR Giveaway
Package, and the other a Beamer LaTeX presentation
of the talk, as presented.

## Pamphlet: Getting Started With Software Defined Radio
This pamphlet is provided as a raffle prize for an attendee
of CPOSC 2018.
The document was aimed at giving the recipient a brief
overview and guide on how to begin using the RTL-SDR,
even if they have not attended the talk.

This document is also provided for use and consumption
of any other person who may be interested.

## Presentation: Decoding Weather Satellites
This Beamer presentation includes the LaTeX files and images
related to the CPOSC 2018 talk.
This presentation covers information on three satellites,
what it looks like when receiving, and what the open-source
decoding programs do 'behind the curtain'.

## Information on Open Source Hardware
The 140 MHz filter referenced in the presentation
and pamphlet is available [here](https://github.com/tomswartz07/140bpf-kicad).
