
[![Python](https://img.shields.io/badge/python-3.8.2-blue.svg)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://choosealicense.com/licenses/mit/)

# pyMBHdyn

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video Page</title>
    <style>
        .centered-video {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh; /* Optional: Adjust the height as needed */
        }
        body {
            margin: 0;
        }
    </style>
</head>
<body>

<div class="centered-video">
    <video controls>
        <source src="kick.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

</body>
</html>

[pyMBHdyn](https://github.com/Blackholan/pyMBHdyn) is a Python package which tracks the orbit of the central SMBH in 370 bright central galaxies by
using orbital integration methods after analysing the merger history of the central galaxies within its galaxy cluster. pyMBHdyn intensively uses [galpy](https://www.galpy.org/) for galactic dynamics and [IllustrisTNG-300](https://www.tng-project.org/data/downloads/TNG300-1/) to model a realistic galaxy cluster environment.

More details on the method and applications can be found in the paper:

[Off-centre supermassive black holes in bright central galaxies](https://arxiv.org/abs/2212.13277) [code paper]


### Usage

This repository contains: 

* Jupyter notebook
* Input data

## Authors

pyMBHdyn is distributed under the MIT license. See [MIT License](https://en.wikipedia.org/wiki/MIT_License) for more details. 
If you use pyMWGCprogen in a publication, please cite the code paper [Chu et al. +22](https://arxiv.org/abs/2212.13277) and the galpy paper [Bovy +15](https://arxiv.org/abs/1412.3451).

* [Pierre Boldrini](mailto:boldrini@iap.fr) -- Sorbonne University, Institut d'Astrophysique de Paris (IAP), France
* [Aline Chu](mailto:aline.chu96@gmail.com) -- 

