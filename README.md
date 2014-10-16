# BIOMD0000000094: Yamada2003_JAK_STAT_SOCS1_knockout

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000094.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000094.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000094 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


_NCBS Curation Comments:_ This model shows the control mechanism of Jak-Stat
pathway, here SOCS1 (Suppressor of cytokine signaling-I) was identified as the
negative regulator of Jak and STAT signal transduction pathway. This is the
knockout version of Jak-Stat pathway in this model the SOCS1 has been knocked
out i.e it formation is not shown. The graphs are almost similar to the graphs
as shown in the paper but STAT1n graph has some ambiguities. Thanks to Dr
Satoshi Yamada for clarifying some of those ambiguities and providing the
values used in simulations.

_Biomodels Curation Comments:_ The model reproduces the figures 2
(B,D,F,H,J,L,N) corresponding to JAK/STAT activation in SOCS1 knock out cells.
The model was successfully tested on MathSBML

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2006 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .


