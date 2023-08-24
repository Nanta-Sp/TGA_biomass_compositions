# TGA_biomass_compositions
Determination of biomass composition using TGA
(Link to paper to be added soon)

# Files description
M1_Load_Prepare_TGdata_Clean_version.mlx  - Read TGA text file, calculate DTG, and store in DTGdata_biomass.mat
M2_Single_analysis.mlx - Fit with 3 curves and calculate the final composition of cellulose, hemicellulose, and lignin
M3_DTG_fitting.mlx - Fit with 3 or 5 curves return fit result not adjusted

DTGdata_biomass.mat - Store DTG data in struct format
DTG_fit_3curves_biomass_fnc.mlx - matlab function to fit and plot with 3 curves
DTG_fit_5curves_biomass_fnc.mlx - matlab function to fit and plot with 5 curves

# Usage
1. Since there is already some data available, you can try running M2 file directly.
2. To prepare data from TGA text file, use M1. Then, M2.
3. To fit multiple files in sequence with 3 or 5 curves use M3.
