This repository contains the emission line fluxes predicted with the Cloudy photoionization code version 17.01 (Ferland et al. 2017) for the star-forming models described in Section 3.1 of Calabro et al. (2023) (https://arxiv.org/abs/2306.08605). We use for the calculations the package pyCloudy v.0.9.11 (https://github.com/Morisset/pyCloudy/tree/0.9.11). 
Each table contains the predictions of the volume averaged emissivity (obtained with the command get_emis_vol in pycloudy) for a specific emission line (relative to H-beta) specified in the filename, as a function of the following model parameters : 
dens : gas density of the cloud (in units of 1/cm^3 and logarithmic scale)
met : gas-phase metallicity 
OH : corresponding oxygen abundance of the cloud (12+log(O/H))
logU : ionization parameter
In all cases, the incident radiation field shape is obtained with BPASS stellar population models (Eldridge et al. 2017), assuming a Salpeter IMF with an upper mass limit of 300 Msun, stellar metallicity equal to the gas phase metallicity of the surrounding gas cloud, and continuous star-formation history with age of 10^8 yr. 

Currently, the flux predictions are available for the following emission lines :
H$\alpha$
C__1_985026A_SF.txt
H__1_128180M_SF.txt
S__3_953062A_SF.txt
H__1_109380M_SF.txt
P__2_118828M_SF.txt
FE_2_164355M_SF.txt
H__1_187510M_SF.txt
FE_2_125668M_SF.txt
N__2_658345A_SF.txt
H__1_656281A_SF.txt
O__3_500684A_SF.txt
H__1_486133A_SF.txt
