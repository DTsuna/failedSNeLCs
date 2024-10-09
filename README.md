# failedSNeLCs
This repository saves the light curve data for our paper "Transients by Black Hole Formation from Red Supergiants: Impact of Dense Circumstellar Matter" (arXiv:2410.XXXXX), calculated using the code [SNEC](https://stellarcollapse.org/index.php/SNEC.html). 

The model parameters (progenitor mass, CSM profile, explosion energy) adopted are in each filename. Files with "Mdot" are for the superwind profiles with the number being the mass-loss rate in Msun/yr (for wind speed of 50 km/s), and those with "vrat" are for the dense chromosphere model by [Fuller & Tsuna (2024)](https://doi.org/10.33232/001c.120130) with the number being the characteristic parameter v_con/v_esc (envelope convective velocity over surface escape velocity, typically in the range 0.08-0.1) that sets the density profile in their model.

Columns are time from energy injection [days], luminosity [erg/s], effective temperature [K]. The plots for all the bolometric light curves are accessible in SNEC_plots.pdf

The light curve starts at 3 days before the time of shock breakout (recorded in SNEC), and continues with timestep of 0.02 days until 1000, 700 and 500 days from energy injection for the 1e48 erg, 3e48 erg, 1e49 erg respectively.
