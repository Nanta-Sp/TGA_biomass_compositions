# TGA_biomass_compositions
Determination of biomass composition (cellulose, hemicellulose, lignin) using TGA <br>
The total wt% dry basis  = extractives + ash (partial) + cellulose + hemicellulose + lignin <br>
More detail in (Link to paper to be added soon)

# Input require
1. TGA text file <br>
2. Extractives analysis results of sample in wt%db <br>
3. Ash content of the extractives-free sample in wt% of extractives-free sample <br>

# Files description
<b>M1_Load_Prepare_TGdata_Clean_version.mlx </b>  - Read TGA text file, calculate DTG, and store in DTGdata_biomass.mat <br>
<b>M2_Single_analysis.mlx</b> - Fit with 3 curves and calculate the final composition of cellulose, hemicellulose, and lignin <br>
<b>M3_DTG_fitting.mlx</b> - Fit with 3 or 5 curves return fit result not adjusted <br>
<br>
<b>DTGdata_biomass.mat</b> - Store DTG data in struct format <br>
<b>DTG_fit_3curves_biomass_fnc.mlx</b> - matlab function to fit and plot with 3 curves <br>
<b>DTG_fit_5curves_biomass_fnc.mlx</b> - matlab function to fit and plot with 5 curves <br>

# Usage
1. Since there is already some data available, you can try running M2 file directly. <br>
2. To prepare data from TGA text file, use M1. Then, M2. <br>
3. To fit multiple files in sequence with 3 or 5 curves use M3. <br>
<br>
<b> Contact</b>: nanta @ umich . edu
