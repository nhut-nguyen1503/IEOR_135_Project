# SF Crime README

## Installing Python Libraries
#### Anaconda
If anaconda is not yet installed (conda commands cannot be run), follow the instructions to install anaconda here: https://docs.conda.io/en/latest/miniconda.html

#### Models and Forecasting Packages
Once anaconda is installed (conda commands can already be run), install the following packages:


| Use | Python Library |
| ------ | ------ |
| Seasonal Decompose Analysis | [statsmodels.tsa.seasonal] |
| SARIMA Model | [statsmodels.tsa.statespace.sarimax] |
| Triple Exponential Smoothing Model | [statsmodels.tsa.holtwinters] |
|  Random Forest, Gradient Boosting, Adaboosting Model | [sklearn.ensemble] |
|  Location Search | [geopy.geocoders] |

The packages can  be installed using a command line prompt similar to the example provided below.
```sh
conda install [package name]
```

## Installing the User Interface
#### IPython Widgets
Our interative UI uses IPython widgets. Please install the IPython widgets package to enable interactions with the visualizations. Documentation to install IPython widgets can be found at [ipywidgets installation].

```sh
conda install -c conda-forge ipywidgets
```

#### Plotly
Our data visualizations make use of Plotly. Documentation to install Plotly can be found at [plotly installation].
```sh
conda install -c plotly plotly=4.7.0
```

#### Voila
Our user interface runs on the Voila visualization engine add-on for Jupyter notebook. Install Voila on your computer using the following command. Further documentation to install Voila can be found at [voila installation].
```sh
conda install voila -c conda-forge
```

## Running the Program
Once all the packages are installed, the UI can be run. From your Anaconda command prompt enter:
```sh
voila
```
A window on your default internet broswer should open where you can navigate to the directory with your Jupyter notebook files. Select the Dashboard_UI.ipynb. A Voila loading symbol will appear as the notebook is being rendered. Shortly after the interactive Voila interface should open. A video demo of our project can be found at [UI Demo].

[ipywidgets installation]: <https://ipywidgets.readthedocs.io/en/latest/user_install.html>
[plotly installation]: <https://plotly.com/python/getting-started/?utm_source=mailchimp-jan-2015&utm_medium=email&utm_campaign=generalemail-jan2015&utm_term=bubble-chart>
[voila installation]: <https://blog.jupyter.org/and-voil%C3%A0-f6a2c08a4a93>
[statsmodels.tsa.seasonal]: <https://www.statsmodels.org/stable/generated/statsmodels.tsa.seasonal.seasonal_decompose.html>
[statsmodels.tsa.statespace.sarimax]: <https://www.statsmodels.org/dev/generated/statsmodels.tsa.statespace.sarimax.SARIMAX.html>
[statsmodels.tsa.holtwinters]: <https://www.statsmodels.org/stable/generated/statsmodels.tsa.holtwinters.ExponentialSmoothing.html>
[sklearn.ensemble]: <https://scikit-learn.org/stable/modules/ensemble.html>
[geopy.geocoders]: <https://geopy.readthedocs.io/en/stable/>
[UI Demo]: <https://www.youtube.com/watch?v=i-V_IjnNgLA>
