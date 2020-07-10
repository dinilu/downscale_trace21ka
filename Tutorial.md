# Paleoclimate data
Paleoclimate data comes from the Trace-21ka simulation using the CESM climate model: http://www.cgd.ucar.edu/ccr/TraCE/

A dictionary of the output variables from the model is available here: http://www.cesm.ucar.edu/projects/community-projects/LENS/data-sets.html

After checking the relevant variables I came to the conclusion that I should use: tsmn (minimum surface temperature over output period), tsmx (maximum surface temperature over output period), and ¿precc/precl? (convective precipitation rate (liq+ice)/large scale precipitation rate (liq+ice)).

Downloads are from this link: https://www.earthsystemgrid.org/project/trace.html. The selected dataset is "Main TraCE dataset". 

From supplementary information (http://www.ecography.org/appendix/ecog-03031) in Fordham et al. (2017)<sup>[1]</sup>: "We derived a correction factor for each variable, month and grid cell in PaleoViewusing the differences between the observed and modelled climate for an 11-year period (1979 through 1989) centered on 1985. Observed climate data came from the ERA interim (Dee, D. P. et al. 2011)and MERRA reanalyses (Rienecker, M. M. et al. 2011). This procedure is often referred to as “bias correction”." Specific formulas can be found also in the supplementary information if needed (I may not needed by using the climate4R bundle (framework).

A presentation of the climate4R framework can be found in Iturbide et al. (2019)[2]. They provide also some examples and links to the wiki pages for the different constituent R-packages.

I need to follow those tutorial and examples with the Trace-21ka data.

# References

[1] Fordham, D.A., Saltré, F., Haythorne, S., Wigley, T.M.L., Otto‐Bliesner, B.L., Chan, K.C. and Brook, B.W. (2017), PaleoView: a tool for generating continuous climate projections spanning the last 21 000 years at regional and global scales. Ecography, 40: 1348-1358. doi:10.1111/ecog.03031

[2] Iturbide, M., Bedia, J., Herrera, S., Baño-Medina, J., Fernández, J., Frías, M. D., Manzanas, R., San-Martín, D., Cimadevilla, E., Cofiño, A. S., & Gutiérrez, J. M. (2019). The R-based climate4R open framework for reproducible climate data access and post-processing. Environmental Modelling & Software, 111, 42–54. https://doi.org/10.1016/j.envsoft.2018.09.009


