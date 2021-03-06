# Source code repository for the paper "Radial Intersection Count Image: a Clutter Resistant Shape Descriptor"

[Please find the paper on which this work is based here](https://www.sciencedirect.com/science/article/pii/S0097849320301096)

-----

### Notice: This repository is for archival and reproduction purposes only. 

### Please refer to the following repositories for updated code and documentation:

[libShapeDescriptor](https://github.com/bartvbl/libShapeDescriptor)


[Clutterbox](https://github.com/bartvbl/Clutterbox)

-----

This repository contains:

- A reference implementation of the Radial Intersection Count Image
- Efficient GPU implementations of the Spin Image and 3D Shape Context descriptors
- A reference implementation of the Clutterbox Experiment
- A script which can be used to completely reproduce all results presented in the paper

## Instructions

You can run the start the script by running:

```bash

python3 replicate.py

```

From the root of the repository.

Refer to the included Manual PDF for further instructions.

## System Requirements

The RAM and Disk space requirements are only valid when attempting to reproduce the presented results.

The codebase _should_ be able to compile on Windows, but due to some CUDA driver/SDK compatbility issues we have not yet been able to verify this.

Type | Requirements
-----|----------------------------------------------------------------------------
CPU  | Does not matter
RAM  | At least 32GB
Disk | Must have about ~70GB of storage available to store the downloaded datasets
GPU  | Any NVIDIA GPU (project uses CUDA)
OS   | Ubuntu 16 or higher. Project has been tested on 18 and 20.

## Credits

- Development and implementation: Bart Iver van Blokland, [NTNU Visual Computing Lab](https://www.idi.ntnu.no/grupper/vis/)
- Supervision: Theoharis Theoharis, [NTNU Visual Computing Lab](https://www.idi.ntnu.no/grupper/vis/)

If you use (parts of) this library in your research, we kindly ask you reference the papers on which this project is based:

    @article{van2020radial,
      title={Radial intersection count image: A clutter resistant 3D shape descriptor},
      author={van Blokland, Bart Iver and Theoharis, Theoharis},
      journal={Computers \& Graphics},
      volume="91",
      pages="118--128",
      year={2020},
      publisher={Elsevier}
    }
    
    @article{van2020indexing,
      title={An Indexing Scheme and Descriptor for 3D Object Retrieval Based on Local Shape Querying},
      author={van Blokland, Bart Iver and Theoharis, Theoharis},
      journal={Computers \& Graphics},
	  volume="92",
	  pages="55--66",
      year={2020},
      publisher={Elsevier}
    }

