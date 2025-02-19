This is a forked branch of Transrate 1.0.4 that will work with Salmon 0.8.2

To install this unreleased version of Transrate 1.0.4

$ git clone https://github.com/dfmoralesb/transrate.git

$ cd transrate

$ gem build transrate.gemspec

make a directory where you will install the transrate 

$ mkdir /home/morales/Apps/gems

install the gem

$ gem install ~/Apps/transrate/transrate-1.0.3.gem --install-dir /home/morales/Apps/gems --verbose

create a conda environment with the specific version of salmon and blast (version of blast can be changed in `transrate/deps/blast.yaml`)

conda create --name transrate salmon=0.8.2 blast=2.9.0

run transrate in the conda env


Then follow the instructions from [Transrate](http://hibberdlab.com/transrate/)
