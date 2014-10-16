# MODEL0406793751: Pasek2008_VentricularCardioMyocyte

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL0406793751.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL0406793751.git@20140916`

## Usage

Importing the model package.

`import MODEL0406793751 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**A model of the guinea-pig ventricular cardiac myocyte incorporating a transverse-axial tubular system.**   
Pásek M, Simurda J, Orchard CH, Christé G. _Prog Biophys Mol Biol._ 2008 Jan-
Apr;96(1-3):258-80. [17888503](http://www.ncbi.nlm.nih.gov/pubmed/17888503) ,  
**Abstract:**   
A model of the guinea-pig cardiac ventricular myocyte has been developed that
includes a representation of the transverse-axial tubular system (TATS),
including heterogeneous distribution of ion flux pathways between the surface
and tubular membranes. The model reproduces frequency-dependent changes of
action potential shape and intracellular ion concentrations and can replicate
experimental data showing ion diffusion between the tubular lumen and external
solution in guinea-pig myocytes. The model is stable at rest and during
activity and returns to rested state after perturbation. Theoretical analysis
and model simulations show that, due to tight electrical coupling, tubular and
surface membranes behave as a homogeneous whole during voltage and current
clamp (maximum difference 0.9 mV at peak tubular INa of -38 nA). However,
during action potentials, restricted diffusion and ionic currents in TATS
cause depletion of tubular Ca2+ and accumulation of tubular K+ (up to -19.8%
and +3.4%, respectively, of bulk extracellular values, at 6 Hz). These
changes, in turn, decrease ion fluxes across the TATS membrane and decrease
sarcoplasmic reticulum (SR) Ca2+ load. Thus, the TATS plays a potentially
important role in modulating the function of guinea-pig ventricular myocyte in
physiological conditions.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Pásek M, Simurda J, Orchard CH, Christé G. (2008)
- version03**
](http://www.cellml.org/models/pasek_simurda_orchard_christe_2008_version03)  
The original CellML model was created by:  
**Lloyd, Catherine, May**   
c.lloyd@aukland.ac.nz  
The University of Auckland  
The Bioengineering Institute  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


