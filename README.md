Plotting and analysis of [eWaterCycle forecast](http://forecast.ewatercycle.org/) output using Jupyter lab notebooks.

# RUN

Start Jupyter with

```bash
docker run -e NB_UID=$(id -u) -e NB_GID=$(id -g) -v $PWD:/home/jovyan -it --rm -p 8888:8888 ewatercycle/jupyterlab-experiment-builder
```

A url will be printed which you can open in a web browser.
Open the notebooks (*.ipynb) to view and re-rerun them.
