# Openmod visualisation tutorial

Authors: Bryn Pickering, Stefan Pfenninger

License: MIT

## About

A tutorial on how to visualise data with Python, consisting of three Jupyter Notebooks:

* [01-matplotlib.ipynb](01-matplotlib.ipynb) shows how to use matplotlib, the workhorse of plotting in Python, together with pandas and seaborn.
* [02-web-based.ipynb](02-web-based.ipynb) introduces Plotly and Bokeh, modern web-based libraries which make it very easy to create interactive visualisations.
* [03-touching-up.ipynb](03-touching-up.ipynb) shows how to save vector graphics from matplotlib, Plotly or Bokeh for final touching up in a separate tool, for example the free and open-source [Inkscape](http://inkscape.org/).

## Setup

### Environment

Create a new conda environment with the required packages:

```bash
$ conda env create -f requirements.yml
```

### Data

We are using data made available from the Open Power System Data project for this tutorial. These datasets can be found in the `data` subdirectory and are based on the following download links:

* [time_series_60min_singleindex.csv](https://data.open-power-system-data.org/index.php?package=time_series&version=2017-07-09&action=customDownload&resource=3&filter%5B_contentfilter_utc_timestamp%5D%5Bfrom%5D=2011-01-01&filter%5B_contentfilter_utc_timestamp%5D%5Bto%5D=2016-12-31&filter%5BRegion%5D%5B%5D=CZ&filter%5BRegion%5D%5B%5D=DE&filter%5BRegion%5D%5B%5D=DK&filter%5BRegion%5D%5B%5D=SE&filter%5BVariable%5D%5B%5D=solar&filter%5BVariable%5D%5B%5D=wind&filter%5BVariable%5D%5B%5D=wind_offshore&filter%5BVariable%5D%5B%5D=wind_onshore&filter%5BAttribute%5D%5B%5D=generation&downloadCSV=Download+CSV)
* [conventional_power_plants_DE.csv](http://data.open-power-system-data.org/conventional_power_plants/2017-03-03/conventional_power_plants_DE.csv)
* [conventional_power_plants_EU.csv](http://data.open-power-system-data.org/conventional_power_plants/2017-03-03/conventional_power_plants_EU.csv)

## Other libraries we don't cover here

* d3 (e.g. [mpld3](https://mpld3.github.io/))
* [airbnb superset](https://github.com/airbnb/superset)
* [vega](https://vega.github.io/vega/)
* [altair](https://altair-viz.github.io/)
