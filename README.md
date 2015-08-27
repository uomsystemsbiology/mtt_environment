### Overview

This is the reference environment for the manuscript ['Hierarchical Bond Graph Modelling of Biochemical Networks'](http://arxiv.org/abs/1503.01814).  It executes code to reproduce specific results described in the manuscript.   You can find more information about this research at the [project page here](http://uomsystemsbiology.github.io/hbgm/).  

To find other versions of this reference environment, see Other Links below.  To learn more about reference environments, [see the detailed description here](http://uomsystemsbiology.github.io/reference-environments/).  

### Instructions for use

This version of the reference environment is a virtual machine managed by [Vagrant](http://www.vagrantup.com).  To use it, install [Vagrant](http://www.vagrantup.com) and [VirtualBox](https://www.virtualbox.org/), then do:

```
$ git clone https://github.com/uomsystemsbiology/hbgm_reference_environment.git
$ cd project_name
$ vagrant up
$ vagrant reload
```
This will start a virtual machine with scripts to run which reproduce results described in the manuscript.  

### Other links

[Manuscript link](http://arxiv.org/abs/1503.01814)

[Project page link](http://uomsystemsbiology.github.io/hbgm/)

[Docker container](https://hub.docker.com/r/uomsystemsbiology/hbgm/)

[Bootable ISO](https://dx.doi.org/10.5281/zenodo.29623)
