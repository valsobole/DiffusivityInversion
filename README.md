# DiffusivityInversion
https://doi.org/10.5281/zenodo.4661951

Separate and joint inversion for diffusivity using the Jacob-Ferris model and all dominant frequencies.

The code is shared as a part of submission to WRR journal (DOI will be updated after the publication).
If any parts of the code are used or reprodused the original sourse and the author must be cited.
Any questions can be addressed to the author @ valeriia.sobolevskaia@gmail.com

The structure of the folders should remain the same as in the zip folder for flawless work.
Set your working directory to the .m (code) file location.

Running the flow:
1. Select working wells (lines 42 and 43) and run the workflow
2. Select working widnow from the pop-up window (Figure 1)
3. QC the plots. If any identified freuqncies are not correct, adjust parameters on lines 150-155 (repeat at 260-265).
4. QC the stability of the results from Figures 5-6 and adjust the time window (step 2) if needed.
5. Ones satisfied with the results, adjust number of Monte-Carlo simulations to a desired value (line 613).
6. Collect the final values.
