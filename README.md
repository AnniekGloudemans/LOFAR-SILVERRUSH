# LOFAR-SILVERRUSH

Here the key results of the paper "LOFAR Properties of SILVERRUSH Lyman Alpha Emitter Candidates in the ELAIS-N1 Field" are shown (Gloudemans, Duncan et al. to be submitted).

## Abstract
Lyα emitters (LAEs) in the Epoch of Reionization (EoR) offer valuable probes of both early galaxy evolution and the process of
reionization itself, however the exact evolution of their abundance and the nature of their emission remains an open question. We
combine samples of 229 and 349 LAE candidates at z = 5.7 and z = 6.6 respectively from the SILVERRUSH narrowband survey
with deep Low Frequency Array (LOFAR) radio continuum observations in the ELAIS-N1 field to search for radio galaxies in the
EoR and study the low-frequency radio properties of z 􏰀 5.7 LAE emitters. Our LOFAR observations reach an unprecedented depth
of ∼ 20 μJy beam−1 at 150MHz, and we detect 5 candidate LAEs at > 5σ significance. Based on detailed spectral energy distribution
(SED) modelling of independent multi-wavelength observations in the field, we conclude that these sources are likely [OII] emitters
at z = 1.47, yielding no reliable z 􏰀 5.7 radio galaxy candidates. We examine the 111 z = 5.7 and z = 6.6 LAE candidates that
are undetected in by LOFAR but have optical counterparts in our panchromatic photometry catalog, finding contamination rates of
52-92 and 77-93% for the z = 5.7 and z = 6.6 subset of the LAE candidate samples respectively. Contamination of these optically
bright LAE samples by likely [OII] emitters is lowered significantly through constraints on the near-infrared colors, highlighting the
need for infrared observations to robustly identify LAEs in narrowband surveys. Finally, stacking of radio continuum observations for
the robust LAE samples yields a 2σ upper limit on radio luminosity of 8.2×10^23 and 8.7×10^23 W/Hz at z = 5.7/6.6 respectively,
 corresponding to limits on their median star-formation rates of <53 and 56 M⊙ yr .

## Key results
![alt text](https://github.com/AnniekGloudemans/LOFAR-SILVERRUSH/blob/master/multiwavelength_cutouts_5_sources.png)
Fig 1: Multi-wavelength cutouts of the 5 sources in the LOFAR detected sample including from left to right: HSC r band, HSC z band, HSC NB921 band, UKIDSS K band, IRAC 4.5 μm, LOFAR 150 MHz. The sources show negligible or no emission below the Lyman break in the r band, however clear emission is seen in both UKIDSS k band and IRAC.

![alt text](https://github.com/AnniekGloudemans/LOFAR-SILVERRUSH/blob/master/sed_fitting_candidate_ILTJ160658.74+550607.0.png)
Fig 2: SED fitting results for the most promising source ILTJ160658.74+550607.0, obtained using Bagpipes. Left: Reduced χ2 for SED fits in the range 0 < z < 8, with locations of Lyα, [OII], and [OIII]+Hβ emission line indicated by black dashed lines. The grey dashed lines indicate the redshift range probed by the NB filter for the strong emission lines [OIII], [OII], as well as Lyα. Right: observed flux of ILTJ160658.74+550607.0 (blue) in mJy with the original errors and posterior median model (yellow) for fits with redshifts fixed at z =0.84, 1.47, and 6.57. The source is best fitted by a template with z=1.47 when considering the possible emission lines. No other emission line is strong enough for the source to be at z ∼ 4. SED fitting on the other sources, suggests all 5 sources are [OII] emitters at z=1.47.


![alt text](https://github.com/AnniekGloudemans/LOFAR-SILVERRUSH/blob/master/LOFAR_stacks_all.png)
Fig 4: Stacked LOFAR cutouts of LAE candidates SILVERRUSH samples. Left: NB816 full sample (226 sources; upper left), optically- selected sample (53 sources; middle left), and likely Lyα emitters (177 sources; bottom left). Right: NB921 full sample (322 sources; upper right), optically-selected sample (49 sources; middle right), and likely Lyα emitters (279 sources; bottom right). LOFAR detected sources and sources not overlapping with LOFAR coverage have been removed. We set limits on the radio luminosity of the LAE population of 8.2x10^23 and 8.7x 10^23 W/Hz at z=5.7 and 6.6 respectively, corresponding to limits on their median star formation rate of < 53 and 56 M⊙ /yr.

![alt text](https://github.com/AnniekGloudemans/LOFAR-SILVERRUSH/blob/master/lofar_silverrush_pz_stack.png)

Fig 5: stacked photometric redshift probability distribution of the optically cross-matched sample of NB921 and NB816 LAE catalogs from Duncan et al 2020 (to be submitted). The known possible redshifts from the NB emission line detections and more detailed SED fitting allows to exclude other high-z solutions that are sometimes favored by the photometric redshift code.

![alt text](https://github.com/AnniekGloudemans/LOFAR-SILVERRUSH/blob/master/J_K_mag_photoz_optically_selected.png)
Fig 6: UKIDSS J and K band magnitude of the optically-selected sample and LOFAR detected sample, with color coded photo-zs from Duncan et al 2020. The diagonal (dashed) line indicates the J−K ≤ 0 criterion. The sources above this line satisfy this criterion and also have notably higher photo-z values.

![alt text](https://github.com/AnniekGloudemans/LOFAR-SILVERRUSH/blob/master/sed_fits_stacks.png)
Fig 7: Left: Stacked SED of likely z = 6.6 LAE candidates in the NB921 catalog, consisting of the non-matched sample and probable LAEs in the matched sample. Right: Stacked SED of likely contaminants in the NB921 matched optical sample, fitted with fixed z = 1.47. The stack of likely contaminants shows brighter NIR and MIR fluxes highlighting the importance of using NIR data in LAE selection.
