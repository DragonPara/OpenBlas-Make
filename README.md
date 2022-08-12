# OpenBlas-Make

## environment: 
* redhat
* gcc version 4.8.5 20150623 (Red Hat 4.8.5-36) (GCC)
## compile
```shell
make CC=gcc FC=gfortran make_NB_JOBS=1
make install PREFIX=<install_path>
```
if you don't make with suffix `make_NB_JOBS`, and has a old lapack in you machine,

openblas will generate before included lapack built, And won't call the old lapack lib.
