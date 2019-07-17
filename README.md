[![Build Status](https://travis-ci.org/TUW-GEO/rt1.svg?branch=master)](https://travis-ci.org/TUW-GEO/rt1) [![Documentation Status](https://readthedocs.org/projects/rt1/badge/?version=latest)](http://rt1.readthedocs.io/)

# RT1 - bistatic scattering model for first order scattering of random media

The package implements a first order scattering radiative transfer model
for random volume over ground as documented in *Quast & Wagner (2016)* and
*Quast, Albergel, Calvet, Wagner (2019)*

The documentation of the package is found [here](http://rt1.readthedocs.io/).
(Note that the documentation is still under construction.)

## Usage

Any usage of this code is subject to the following conditions

* full compliance with the license (see LICENSE file) is given
* In publications or public presentations, credit should be given to the
  authors by mainly a) citing the references below, b) pointing to this
  github repository

## Installation
For a basic install, the following line should be fine:

    pip install rt1

In order to get the full functionality of the symbolic computations,
it is currently required to install a specific commit of symengine, i.e.:

    conda install -c symengine/label/dev python-symengine=0.3.0.84
    pip install rt1

## References
* Quast & Wagner (2016): [doi:10.1364/AO.55.005379](https://doi.org/10.1364/AO.55.005379)
* Quast, Albergel, Calvet, Wagner (2019) : [doi:10.3390/rs11030285](https://doi.org/10.3390/rs11030285)

