# SESNtemple

This repository contains data products from [Liu & Modjaz (2014)](http://adsabs.harvard.edu/abs/2014arXiv1405.1437L), [Liu et al. (2016)](http://adsabs.harvard.edu/abs/2015arXiv151008049L), and [Modjaz et al. (2016)](http://adsabs.harvard.edu/abs/2015arXiv150907124M) on Stripped Envelope SNe (SESN), ie SNe of types IIb, Ib, Ic and Ic-bl. There are two different types of SN templates we produced and used in our research, which are stored in two different folders:
- <b>/MeanSpec</b> contains all mean spectra and standard deviation spectra of different SESN types in [Liu et al. (2016)](http://adsabs.harvard.edu/abs/2015arXiv151008049L), and [Modjaz et al. (2016)](http://adsabs.harvard.edu/abs/2015arXiv150907124M), including those not shown in plots. Mean-spectra and standard deviation spectra can be used to quantify SN diversity, determine if a new transient is a novel type of explosion, and so on. See the README file in the folder for details of the mean-spectra. Mean spectra of SNe Ic are used as SN Ic templates for our template fitting code called "Ic_conv_Icbl_MCMC.py" (https://github.com/nyusngroup/SESNspectraLib), which measures line velocities in SNe Ic-bl based on blended lines. They live under the SESNspectraLib repository, since we want the template fitting code to be self-contained, and since those mean spectra templates were constructed from SN Ic spectra using slightly different phase ranges than the ones released here.
 
- <b>/SNIDtemplates</b> contains all SuperNova IDentification (SNID; [Blondin & Tonry 2007](http://adsabs.harvard.edu/abs/2007ApJ...666.1024B)) templates that were released in [Liu & Modjaz (2014)](http://adsabs.harvard.edu/abs/2014arXiv1405.1437L), and used in [Liu et al. (2016)](http://adsabs.harvard.edu/abs/2015arXiv151008049L), and [Modjaz et al. (2016)](http://adsabs.harvard.edu/abs/2015arXiv150907124M). Adding these templates to the spectra library database of SNID will increase the number of SESN templates in the database, which will help SN classification via SNID. See the README file in the folder for details of SN spectra that are used to construct SNID templates.


If you use data products in this repository, please <b>acknowledge</b> this work by including in your paper:

	This work made use of the data products generated by the NYU SN group, and 
	released under DOI:10.5281/zenodo.?????, 
	available at \url{https://github.com/nyusngroup/SESNtemple/}.
	  
*and* <b>cite</b> the appropriate reference(s):

Liu & Modjaz (2014):

  	@ARTICLE{2014arXiv1405.1437L,
    	author = {{Liu}, Y. and {Modjaz}, M.},
     	title = "{SuperNova IDentification spectral templates of 70 stripped-envelope core-collapse supernovae}",
   	journal = {ArXiv e-prints},
  	archivePrefix = "arXiv",
     	eprint = {1405.1437},
   	primaryClass = "astro-ph.SR",
   	keywords = {Astrophysics - Solar and Stellar Astrophysics, Astrophysics - High Energy Astrophysical Phenomena},
       	year = 2014,
     	month = may,
    	adsurl = {http://adsabs.harvard.edu/abs/2014arXiv1405.1437L},
	  adsnote = {Provided by the SAO/NASA Astrophysics Data System}
  	}

Liu et al. (2016):

	 @ARTICLE{2015arXiv151008049L,
     	author = {{Liu}, Y.-Q. and {Modjaz}, M. and {Bianco}, F.~B. and {Graur}, O.
		  },
      	title = "{Analyzing the Largest Spectroscopic Dataset of Stripped Supernovae to Improve Their Identifications and   Constrain Their Progenitors}",
    	journal = {ArXiv e-prints},
  	archivePrefix = "arXiv",
     	eprint = {1510.08049},
  	primaryClass = "astro-ph.HE",
   	keywords = {Astrophysics - High Energy Astrophysical Phenomena, Astrophysics - Solar and Stellar Astrophysics},
	 year = 2016,
      	month = oct,
    	adsurl = {http://adsabs.harvard.edu/abs/2015arXiv151008049L},
    	adsnote = {Provided by the SAO/NASA Astrophysics Data System} 
	 }

Modjaz et al. (2016):
  
	  @ARTICLE{2015arXiv150907124M,
     	author = {{Modjaz}, M. and {Liu}, Y.~Q. and {Bianco}, F.~B. and {Graur}, O.
		  },
      	title = "{The Spectral SN-GRB Connection: Systematic Spectral Comparisons between Type Ic Supernovae, and broad-lined 	Type Ic Supernovae with and without Gamma-Ray Bursts}",
    	journal = {ArXiv e-prints},
  	archivePrefix = "arXiv",
     	eprint = {1509.07124},
  	primaryClass = "astro-ph.HE",
   	keywords = {Astrophysics - High Energy Astrophysical Phenomena, Astrophysics - Solar and Stellar Astrophysics},
       	year = 2016,
      	month = sep,
    	adsurl = {http://adsabs.harvard.edu/abs/2015arXiv150907124M},
    	adsnote = {Provided by the SAO/NASA Astrophysics Data System}
	 }
  
  
