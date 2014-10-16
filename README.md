# MODEL1112110003: Gaetano2008_DiabetesProgressionModel

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1112110003.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1112110003.git@20140916`

## Usage

Importing the model package.

`import MODEL1112110003 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Mathematical models of diabetes progression.**   
De Gaetano A, Hardy T, Beck B, Abu-Raddad E, Palumbo P, Bue-Valleskey J,
Porksen N. _Am J Physiol Endocrinol Metab._ 2008 Dec;295(6):E1462-79.
[18780774](http://www.ncbi.nlm.nih.gov/pubmed/18780774) ,  
**Abstract:**   
Few attempts have been made to model mathematically the progression of type 2
diabetes. A realistic representation of the long-term physiological adaptation
to developing insulin resistance is necessary for effectively designing
clinical trials and evaluating diabetes prevention or disease modification
therapies. Writing a good model for diabetes progression is difficult because
the long time span of the disease makes experimental verification of modeling
hypotheses extremely awkward. In this context, it is of primary importance
that the assumptions underlying the model equations properly reflect
established physiology and that the mathematical formulation of the model give
rise only to physically plausible behavior of the solutions. In the present
work, a model of the pancreatic islet compensation is formulated, its
physiological assumptions are presented, some fundamental qualitative
characteristics of its solutions are established, the numerical values
assigned to its parameters are extensively discussed (also with reference to
available cross-sectional epidemiologic data), and its performance over the
span of a lifetime is simulated under various conditions, including worsening
insulin resistance and primary replication defects. The differences with
respect to two previously proposed models of diabetes progression are
highlighted, and therefore, the model is proposed as a realistic, robust
description of the evolution of the compensation of the glucose-insulin system
in healthy and diabetic individuals. Model simulations can be run from the
authors' web page.

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


