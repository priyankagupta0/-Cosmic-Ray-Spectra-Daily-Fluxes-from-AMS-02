# -Cosmic-Ray-Spectra-Daily-Fluxes-from-AMS-02
Analysis and Visualization of Cosmic Ray Spectra: Daily Fluxes from AMS-02 (Published in PRL 2021)

# AMS-02 Proton Flux Data from PRL 2021: Daily Spectra and Event Selection

In this project, we are working with data related to cosmic rays, specifically focusing on the daily proton flux data collected by the Alpha Magnetic Spectrometer (AMS-02) experiment. 

The dataset presented here comprises the daily proton fluxes from the Alpha Magnetic Spectrometer (AMS-02) as published in the Physical Review Letters (PRL) 2021, focusing on the proton component. This unique dataset offers an opportunity to explore the temporal evolution of cosmic radiation at 1 astronomical unit (AU), representing Earth's orbit around the Sun in interstellar space.

These spectra were measured aboard the International Space Station, situated within Earth's magnetosphere, but meticulously filtered to exclude any influence from the geomagnetic field. This meticulous event selection process is detailed in the article by M. Aguilar et al. (AMS Collaboration) in Phys. Rev. Lett. 114, 171103 (2015). Out of approximately 1.5 x 10^11 cosmic ray events recorded from May 20, 2011, to October 29, 2019, this dataset includes 5.5 x 10^9 protons.

To assess the magnetosphere's impact on cosmic rays, a helpful resource is the COR system web tool, accessible at https://cor.crmodels.org/.

Data Description:
The dataset includes cosmic ray proton spectra collected by the AMS-02 experiment [1], featuring proton fluxes in a CSV file:

**p_AMS_PRL2021_daily.csv**: This data table contains AMS-02 daily proton fluxes collected from May 20, 2011, to October 29, 2019, spanning the rigidity interval from 1 to 100 GV. The data is sourced from the Cosmic Ray Data(CRDB) [2].

References:
1. "Periodicities in the Daily Proton Fluxes from 2011 to 2019 Measured by the Alpha Magnetic Spectrometer on the International Space Station from 1 to 100 GV," Phys. Rev. Lett. 127, 271102, 2021, https://doi.org/10.1103/PhysRevLett.127.271102, PDF: https://journals.aps.org/prl/pdf/10.1103/PhysRevLett.127.271102
2. CSV file source, from Cosmic Ray DataBase (CRDB), https://tools.ssdc.asi.it/CosmicRays/
3. Details about CRDB in V. Di Felice, C. Pizzolotto et al., PoS (ICRC2017) 1073, https://pos.sissa.it/301/1073/pdf

Inspired by: PAVOL BOBIK at https://www.kaggle.com/code/adminpretaktovaniesk/cosmic-rays-spectra-ams-02-daily-fluxes-prl-2021

=> AMS-02: The Alpha Magnetic Spectrometer is a particle physics experiment installed on the International Space Station (ISS). It is designed to measure cosmic rays, including protons, electrons, and other particles, in space.
=> Daily Spectra: "Spectra" in this context refers to the distribution of cosmic rays (in this case, protons) at different energies. A "daily spectrum" would show how the number of protons varies at different energy levels each day.
=> Proton Flux: Protons are a type of subatomic particle, and their "flux" refers to the rate at which they arrive at a specific location, usually measured in particles per unit area per unit time. In this project, we are particularly interested in studying the daily variations in the number of protons arriving from space.
