# BIOMD0000000358: BIOMD0000000358

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000358.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000358.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000358 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Stortelder1997 - Thrombin Generation Amidolytic Activity

Mathematical modelling of a part of the blood coagulation mechanism.

This model is described in the article:

[Mathematical modelling in blood coagulation : simulation and parameter
estimation.](http://identifiers.org/narcis/oai:cwi.nl:4725)

Stortelder W.J.H., Hemker P.W., Hemker, H.C.

CWI. Modelling, Analysis and Simulation, No. R 9720, p.1-11.

Abstract:

This paper describes the mathematical modelling of a part of the blood
coagulation mechanism. The model includes the activation of factor X by a
purified enzyme from Russel's Viper Venom (RVV), factor V and prothrombin, and
also comprises the inactivation of the products formed. In this study we
assume that in principle the mechanism of the process is known. However, the
exact structure of the mechanism is unknown, and the process still can be
described by different mathematical models. These models are put to test by
measuring their capacity to explain the course of thrombin generation as
observed in plasma after recalcification in presence of RVV. The mechanism
studied is mathematically modelled as a system of differential-algebraic
equations (DAEs). Each candidate model contains some freedom, which is
expressed in the model equations by the presence of unknown parameters. For
example, reaction constants or initial concentrations are unknown. The goal of
parameter estimation is to determine these unknown parameters in such a way
that the theoretical (i.e., computed) results fit the experimental data within
measurement accuracy and to judge which modifications of the chemical reaction
scheme allow the best fit. We present results on model discrimination and
estimation of reaction constants, which are hard to obtain in another way.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000358](http://identifiers.org/biomodels.db/BIOMD0000000358) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


