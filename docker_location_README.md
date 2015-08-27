### Overview

This is the reference environment for the manuscript ['Hierarchical Bond Graph Modelling of Biochemical Networks'](https://arxiv.org/abs/1503.01814).  It executes code to reproduce specific results described in the manuscript.   You can find more information about this research at the [project page here](https://uomsystemsbiology.github.io/hbgm/).  

To find other versions of this reference environment, see Other Links below.  To learn more about reference environments, [see the detailed description here](https://uomsystemsbiology.github.io/reference-environments/).   

### Instructions for use

This version of the reference environment is a Docker container.  To use it, install [Docker](https://www.docker.com/), then do:

```
$ docker pull uomsystemsbiology/hbgm
$ docker run uomsystemsbiology/hbgm /sbin/my_init -- ./run_experiments.sh
```

This will start the container and execute the scripts which reproduce the results described in the manuscript.  

### Other links

[Manuscript link](https://arxiv.org/abs/1503.01814)

[Project page link](https://uomsystemsbiology.github.io/hbgm/)

[Vagrant-managed virtual machine](https://github.com/uomsystemsbiology/hbgm_reference_environment)

[Bootable ISO](https://dx.doi.org/10.5281/zenodo.29623)

