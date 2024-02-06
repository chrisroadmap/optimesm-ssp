# optimesm-ssp
Produce SSP projections using fair for OptimESM

## Reproduction steps

### Set up conda repository

This assumes that you are using `anaconda` and `python`. Currently, I recommend `python` versions 3.8, 3.9, 3.10 and 3.11. These are the versions supported by `fair` and `fair-calibrate`. Others may work, but these ones are tested.

1. Create your environment:

```
$ conda env create -f environment.yml
```

2. Activate the environment:

```
$ conda activate optimesm-ssp
```

3. Make clean notebooks for version control, which will remove all output and data upon committing, run

```
$ nbstripout --install


### Produce results

Activate the conda environment if you haven't already. Then run

```
$ jupyter notebook
```

Go to the `notebooks` folder, run the notebook, and all results are produced.
