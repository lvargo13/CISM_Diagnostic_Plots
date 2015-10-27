# CISM_Diagnostic_Plots
Diagnostic Plots for CISM


README for CISM_Diagnostic_Plots repo
Lauren Vargo (lvargo13@gmail.com)


run_DiagnosticPlots.sh - bash script to call ncl diagnostic plots
DiagnosticPlots.ncl - plots CISM vs GL data
** These are the scripts that were integrated into LIVV 


----- LIVV --------
Notes on working with Joe to get plots integrated into LIVV
- Sent scripts to Joe in beginning of August, scripts were integrated into LIVV by the end of August
- After sending scripts:	
	- Needed to find a way to share netCDF files (I got an account on Hopper)
	- Needed to give Joe access to my account on Hoopper

Notes on LIVV: 
LIVV Validation website: http://discourse.jhkennedy.org/t/livv-validation/24
- Website includes full descriptions of how to download LIVV and run validation

Running LIVV:
1) Download (or be sure to have) data needed
2) Edit the lvargo13.conf file so that the variables gl_data and model_dir point to the correct locations
3) Run ./livv.py --validation validation/lvargo13/lvargo13.conf
4) Open the www/index.html file in web browser (via the terminal) 



---- Other scripts (not a part of LIVV) ------- 

run_Compare_CISM_plots.sh - bash script to call ncl diagnostic plots
Compare_CISM_plots.ncl - plots CISM vs CISM (to compare different configurations)

plot_TimeSeries.sh - 1.get ice volume and area data from glc.log files 2. call ncl script to plot
plot_TimeSeries.ncl - plot ice volume and area



