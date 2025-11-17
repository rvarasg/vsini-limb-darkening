This repository includes the files used to obtain the results (also here included) in our work "A catalogue of the projected rotational velocity if the CARMENES M-dwarf sample and the effect of limb darkening" that we are about to submit to the Astronomy and Astrophysics journal. 

The files todo_*.bash include the commands used to reduce all the CARMENES-VIS spectra to compute the vsini values, either with oversampled convolution (oc) or with numerical integration (ni). The *_nans.bash include some targets with exceptions to the previous rules. The version of serval we used is also uploaded here, serval_vsini_ld.py, that includes the option to compute the vsini either with OC or NI. The limb dakening coefficients for each spectral order needed for the computation are in ld_coefficients for Teff = 2500, 3000, 3500, and 4000 K. The .csv files include the results for 393 M-dwars of the CARMENES sample.

Here you can find an <a href="https://raw.githack.com/mzechmeister/csvplotter/master/csv_plotter.htm?url=https://raw.githubusercontent.com/rvarasg/vsini-limb-darkening/refs/heads/main/carmenes-vis_vsini_catalogue.csv&cx=$vsini_oc_kms-1&cy=$vsini_literature_kms-1&ce_x=$err_oc_kms-1&ce_y=$err_literature_kms-1&ct=$karmn&cc=$equatorial_velocity_kms-1&funcf=x&funcc=%231f77b4&funco=0.9">interactive plot</a> with the results.

![Image](https://github.com/user-attachments/assets/2a4bc439-0c89-4c0f-819a-bb1b4b17f998)

### Literature references for vsini

- Rein18 — Reiners et al. 2018, *A&A*, 612, 49  
- Fou18 — Fouqué et al. 2018, *MNRAS*, 475, 1960  
- Jen09 — Jenkins et al. 2009, *ApJ*, 704, 975  
- Barn14 — Barnes et al. 2014, *MNRAS*, 439, 3094  
- Del98 — Delfosse et al. 1998, *A&A*, 331, 581  
- Jeff18 — Jeffers et al. 2018, *A&A*, 614, 76  
- MR14 — Martínez-Rodríguez 2014, MSc thesis, Universidad Complutense de Madrid, Spain  
- Bro10 — Browning et al. 2010, *A&A*, 139, 504  
- Tor06 — Torres et al. 2006, *A&A*, 460, 695  
- Marf21 — Marfil et al. 2021, *A&A*, 656, 162


If you have any question, do not hesitate to contact me at rvaras@iaa.es or varas_roberto@outlook.es
