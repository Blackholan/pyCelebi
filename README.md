
[![Python](https://img.shields.io/badge/python-3.8.2-blue.svg)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://choosealicense.com/licenses/mit/)

# pyCelebi (CEntraL massivE Black hole orbital Integration)

<div align="center">
    <a href="kick.mp4" target="_blank">
        <img src="kick.jpeg" alt="Video Thumbnail" ">
    </a>
</div>

</body>

[pyCelebi](https://github.com/Blackholan/pyMBHdyn) is a Python package which tracks the orbit of the central supermassive black hole (SMBH) in 370 bright central galaxies (BCGs) in the Illustris TNG-300 simulation. From the merger history of the central galaxy within its galaxy cluster, pyCelebi uses orbital integration methods to compute the trajectory of the BCG and its SMBH inside the cluster.
#It uses orbital integration methods after analysing the merger history of the central galaxy within its galaxy cluster.# pyCelebi intensively uses [galpy](https://www.galpy.org/) for galactic dynamics and [IllustrisTNG-300](https://www.tng-project.org/data/downloads/TNG300-1/) to model a realistic galaxy cluster environment. Tracking the dynamics of the central SMBH of one BCG from z=2 to z=0 in a BCG+cluster potential including dynamical friction takes of the order of 0.05 CPU hrs.

More details on the method and applications can be found in the paper:

[Off-centre supermassive black holes in bright central galaxies](https://arxiv.org/abs/2212.13277) [code paper]

All the compiled Illustris TNG-300 data for the 370 galaxy clusters used in [Chu et al. +22](https://arxiv.org/abs/2212.13277) are available [here](https://www.iap.fr/useriap/boldrini/data.html).

### Usage

This repository contains: 

* pyCelebi.ipynb, a jupyter notebook that allows running the code.
* Input data for one specific galaxy cluster, as an example.


## Authors

pyCelebi is distributed under the MIT license. See [MIT License](https://en.wikipedia.org/wiki/MIT_License) for more details. 
If you use pyCelebi in a publication, please cite the code paper [Chu et al. +22](https://arxiv.org/abs/2212.13277) and the galpy paper [Bovy +15](https://arxiv.org/abs/1412.3451).

* [Pierre Boldrini](mailto:boldrini@iap.fr) -- Sorbonne University, Institut d'Astrophysique de Paris (IAP), France
* [Aline Chu](mailto:aline.chu96@gmail.com) -- Stockholm University, Oskar Klein Center, Sweden

