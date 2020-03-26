# CS-UCHM
Fortran function that is part of the DarkSUSY library (http://www.darksusy.org/). Written as part of my MSc thesis.
For more details on the quantities involved see https://arxiv.org/abs/1504.01410

Function for calculating the theoretical differential fraction of DM in UCMHs from cosmic string loops  

Authors: Madeleine Anthonisen
          maddyanthonisen@hotmail.com
         Pat Scott
          pscott@imperial.ac.uk
Date: 2014/15

Inputs:  r_cs               cosmic string loop radius (kpc)
         Gmu                cosmic string tension (dimensionless) 
         z_c                latest allowed redshift of UCMH collapse (dimensionless) 
         zstop              redshift at which UCMHs stop growing (dimensionless)
         alpha              ratio of loop length to horizon scale at formation (dimensionless)
         beta               ratio of loop length to loop radius (dimensionless)
         gamma              cosmic string loop decay constant (dimensionless)
         N                  number of loops formed per Hubble 4-volume (dimensionless)
         K                  number of loop radii loops can travel before UCMH formation is impossible (dimensionless)
         sigma              stdev of loop velocity distribution / speed of light (dimensionless)

Output:  dsucmh_f_cs        differential fraction of DM in UCMHs (M_Sun^-1)
