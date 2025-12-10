# fvcom-benchmark-NorthwestPacificSea-1600k

## Run

1. Unpack the compressed file 

```bash
$ tar -xzf inp.tar.gz
```

2. Use the `make.inc` file to generate the FVCOM execution
3. Run the test case in parallel
```bash
$ NP=128
$ mpirun -n ${NP} ./fvcom --casename=hr
```