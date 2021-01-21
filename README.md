# N-body_builder
This repository presents a set of Python utilities to create a tailored to realistic pure N-body model. The tools used here are the 2D photometric tool Imfit and the N-body modelling architecture AGAMA, respectively. Both codes can be consult on their respective papers as follows:

- 2D photometric tool Imfit: Erwin 2015.

- AGAMA galaxy model architecture: Vasiliev 2019.

All the necessary data to initialise and run the scripts are attached in the Zip folder called 'data'. You should download it to your system and unzip in the same directory where you place the jupyter-notebook to read all the necessary files.

The data folder contains the next files:

1. OversamplePSF.fits: the oversample PSF central image of the galaxy in a 251x251 pixels. It's made used to improve the fitting on central region of the HST image.

2. FCC170_HST_croped.fits: the croped HST image of the Fornax galaxy FCC 170 (NGC 1381) used to perform the 2D photometric decomposition.

3. FCC170_pPXF_kinematics_SNR-40.fits: kinematics data proceding from Pinna et al. 2019a obtained by applying the penalized-pixel fitting routine (pPXF) as explained in Cappellari  &  Emsellem  (2004). This .fits file provides the kinematics to compare with our N-body model.

4. consistent_params.ini: parameter file used by AGAMA to produce the initial setup of the N-body model.

## Software requisites

To run the code you will need the following modules (and all the required modules for all of them):

1. numpy

2. matplotlib

3. agama

4. pyimfit

5. astropy

6. acstools

7. mpl_toolkits

8. configparser
