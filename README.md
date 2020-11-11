# Rad-Winds
Data files for the calculation of parameters to characterize radiation driven winds

rho_range.npy = array of densities used, range between 1e-20 - 1e-10 g/cm^3.
T_range.npy = array of temperatures used, range between 5,200 - 70,000 K.
t_grid.npy = array of the CAK t parameter for dimensionless optical depth, range between 1e-15 - 1e1.

alpha_alt.npy = array of alternate fit parameter alpha, 2D array, indexed by density rho index and temperature T index
k_alt.npy = array of alternate fit parameter k, 2D array, indexed by density rho index and temperature T index
s_alt = array of alternate fit parameter s, 2D array, indexed by density rho index and temperature T index

alpha_power.npy = array of CAK power-law fit parameter alpha, 2D array, indexed by density rho index and temperature T index
k_power.npy = array of CAK power-law fit parameter k, 2D array, indexed by density rho index and temperature T index

M_array_fin.npy =  array of calculated force multiplier values, as calculated from spectral line list, 3D array, indexed by density rho index, temperature T index, optical depth t index

Mdot_alt.npy = array of mass loss rates calculated from alternate fit function for force multiplier, 2D array, indexed by density rho index and temperature T index
Mdot_CAK.npy = array of mass loss rates calculated from CAK power-law multiplier form, 2D array, density rho index and temperature T index
Mdot_crit_alt.npy = array of mass loss rates calculated along critical point from alternate force multiplier fit function,2D array, indexed by temperature T index
Mdot_crit_CAK = array of mass loss rates calculated along critical point from CAK power-law force multiplier, 2D array, indexed by temperature T index

param_table.dat = table of the above parameters listed by density and temperature 
