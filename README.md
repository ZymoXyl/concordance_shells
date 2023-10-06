# concordance_shells
Enumerate all concordance shells for each EDO tuning and save result in a .txt file

# Introduction

Equal divisions of the octave (EDO) are musical tuning systems that divide an octave (ratio 2:1) into any number of intervals that are equal on a logarithmic scale, such that the interval perception of any two adjacent pitches is the same. For instance, 12-EDO is the tuning system used ubiquitously throughout Western music today.

A "concordance shell" is defined as an alignment or near-alignment of a set of pitches to just (linear) ratios, or a segment of the harmonic series. The lowest harmonic present is considered the base of the concordance shell. For instance, a set of pitches equal to or approximating intervals defined by the ratios 5:6:7 (e.g. 100Hz:120Hz:140Hz) forms a concordance shell around harmonic 5. A concordance shell formed by near-alignment is called a "virtual alignment object", or VAO for short.

The script concordance_mappings.ipynb enumerates through every EDO tuning from 5-EDO to 53-EDO, and for each tuning, finds concordance shells around each prime harmonic under 100, and records them in a text file along with certain useful information about the harmonics, including the error of the alignment in musical cents and the note in the tuning system that corresponds to the harmonic.
