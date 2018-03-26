Plotting and analysis of [eWaterCycle forecast](http://forecast.ewatercycle.org/) output using Jupyter lab notebooks.

# INSTALL

```bash
cat apt.txt | xargs apt install -y
conda env create -n ecw -f environment.yml
conda activate ecw
./postBuild
```

# RUN

Start Jupyter with

```bash
jupyter lab --ip=0.0.0.0
```

A web browser will open with Jupyter lab enviromnent.
Open the notebooks (*.ipynb) to view and re-rerun them.