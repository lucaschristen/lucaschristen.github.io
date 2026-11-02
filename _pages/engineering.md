---
layout: page
title: Engineering
permalink: /engineering/
description: Experimental hardware, instrumentation, and scientific software developed for research.
nav: true
nav_order: 2
---

My research requires the design, integration, and operation of coupled **laser, vacuum, optical, thermal, and software systems**. This page highlights the engineering methods and technical responsibilities behind the experiments.

## Laser-heated vacuum processing platform

**Scope:** Experimental design · Vacuum systems · Laser integration · High-temperature materials

Design and operation of an experimental system for investigating laser-driven vaporization of lunar regolith simulants under controlled pressure. The setup integrates continuous-wave fiber lasers, sample positioning and motion, high-temperature crucibles, chamber hardware, and optical access for diagnostics.

**Engineering challenges:** Delivering reproducible localized heating, managing thermal loads, maintaining optical access, and obtaining measurements under changing sample conditions.

## Optical pyrometry and closed-loop laser control

**Scope:** Python · Instrumentation · Data acquisition · Feedback control

Development of a Python-based graphical interface linking optical spectroscopy, two-color temperature estimation, laser actuation, and experiment logging. The system supports controlled laser-heating experiments, including time-series temperature and power records.

**Technical focus:** Instrument communication, temperature measurement, feedback stability, experiment reproducibility, and data management.

[View laser-heating and spectroscopy software on GitHub](https://github.com/lucaschristen/PID_SpectraWiz_Laser_Heating)

## Vaporization and compositional depletion modelling

**Scope:** Numerical modelling · Thermodynamics · Python · Scientific analysis

Development of a reduced-order model for temperature-dependent vaporization of multicomponent regolith, including changes in material composition as volatile constituents are removed. The model is used to investigate residence time, material yield, and the potential limits of oxide enrichment.

[View numerical vaporization model on GitHub](https://github.com/lucaschristen/0D_Numerical_Vaporization_Fractional_Loop)

## Experimental diagnostics and optical systems

**Scope:** Optics · Spectroscopy · Measurement design · Calibration

Optical systems for monitoring high-temperature targets and vaporization-related phenomena, using spectrometers, optical filtering, lenses, and calibrated spectral data. This work includes evaluation of measurement uncertainty and integration of optical diagnostics into experimental facilities.

---

**Documentation in progress.** The next update will add annotated laboratory photographs, optical layouts, architecture diagrams, and concise engineering case studies to demonstrate design decisions and validation.
