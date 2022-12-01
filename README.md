# Exciting Instruments Seminar 3

See the companion YouTube video:

[Exciting Seminars | Dr Paul Harris - HUJI | smFRET Data Masterclass FRETBursts & MpH2MM](https://www.youtube.com/watch?v=mH1z_nFoT_E)

Covers how to use FRETBursts and burstH2MM to analyze confocal diffusion based single molecule FRET experiments for rapid within burst dynamics with multi-parameter photon by photon hidden Markov modelling (mpH<sup>2</sup>MM). [Pirchi, Tsukanov et. al. JPC (2016) 51, 13065](https://doi.org/10.1021/acs.jpcb.6b10726), [Harris et. al. Nat Comms (2022) 12, 1000](https://doi.org/10.1038/s41467-022-28632-x)

Make sure to update FRETBursts and burstH2MM:

```
$ pip install --upgrade fretbursts
$ pip install --upgrade bursth2mm
```

## Summary of notebooks

1. [Tutorial.ipynb](https://github.com/exciting-instruments/seminar-003-paul-harris/blob/main/Tutorial.ipynb) Basic tutorial, with explanations of each step, probably the best starting point.
2. [Exciting_Instruments-Partial.ipynb](https://github.com/exciting-instruments/seminar-003-paul-harris/blob/main/Exciting_Instruments-Partial.ipynb) The notebook run during the seminar
3. [How-To-Plotting-Functions.ipynb](https://github.com/exciting-instruments/seminar-003-paul-harris/blob/main/How-To-Plotting-Functions.ipynb) Explains how to customize your plots to look exactly how you want
4. [How-To-ResultsAccess.ipynb](https://github.com/exciting-instruments/seminar-003-paul-harris/blob/main/How-To-ResultsAccess.ipynb) Explains how all results parameter like E, S, dwell based parameters etc. can be accessed, useful if you want to do deeper statistical analysis etc.
5. [How-To-Customization](https://github.com/exciting-instruments/seminar-003-paul-harris/blob/main/How-To-Customization.ipynb) Explains how to use the divisor appraoch to incorporate photon-nanotimes into analysis [Harris, Lerner. Biophysical Reports (2022) 3, 100071)](https://doi.org/10.1016/j.bpr.2022.100071) (not covered during the seminar)
6. [How-To-AccessDivisor.ipynb](https://github.com/exciting-instruments/seminar-003-paul-harris/blob/main/How-To-AccessDivisor.ipynb) Short tutorial on how divisor models are referenced

## Additional Documentation

1. [FRETBursts](https://fretbursts.readthedocs.io)
2. [burstH2MM](https://bursth2mm.readthedocs.io)
