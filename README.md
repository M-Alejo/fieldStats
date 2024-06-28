# Field Stats

[![QGIS.org](https://img.shields.io/badge/QGIS.org-published-green)](https://plugins.qgis.org/plugins/field_stats/)

The Field Stats Plugin allows you calculate basic statistics and create a histogram and boxplot for numeric fields in vector layers.

Your QGIS installation must have [pandas](https://pandas.pydata.org/) and [matplotlib](https://matplotlib.org/)

## How to install
![Plot interactions](img/how_to_install.gif)

The next images show you how to install
![Plot interactions](img/img_install_1.png)
![Plot interactions](img/img_install_2.png)
![Plot interactions](img/img_install_3.png)

## How to use
Field Stats can make the stats and graph for all features or only selected features and you can round the statistics to desire decimal

All Features

![Plot interactions](img/how_to_use_1.gif)

Selected Features

![Plot interactions](img/how_to_use_2.gif)

Next image resume how to use

![Plot interactions](img/img_usage.png)

## How to install Pandas and matplotlib library in Windows
Your QGIS installation must have [pandas](https://pandas.pydata.org/) and [matplotlib](https://matplotlib.org/), in Windows with the OSGeo installer follow the next steps if don't have the libraries.

Search the OSGeo4W in windows menu and select Setup option

![Plot interactions](img/img_1_windows.png)

Select advanced install and clic in next (siguiente)

![Plot interactions](img/img_2_windows.png)

Select intall from internet and clic in next (siguiente)

![Plot interactions](img/img_3_windows.png)

Select your root directory, most of the time it set correct root and you don't have to change, it correspond to first installation of QGIS

![Plot interactions](img/img_4_windows.png)

Select your package directory, most of the time it set correct, and you don't have to change, it correspond to first installation of QGIS

![Plot interactions](img/img_5_windows.png)

Select Use System Proxy Settings and clic in next (siguiente)

![Plot interactions](img/img_6_windows.png)

Select the first option to download the packages from that URL and clic next (siguiente)

![Plot interactions](img/img_7_windows.png)

Type Pandas or Matplolib, to install the library, when you don't have the library it appears like `Source`, clic in `Source` to change for `Install`, If you already installed you see `Keep`

![Plot interactions](img/img_8_windows.png)

Wait to installation to finish and clic on `Finish`
![Plot interactions](img/img_9_windows.png)

If you are using the plugin on MacOS or Linux install the libraries using `pip`, `conda` or `mamba` command, its on your hands. Better if you have installed QGIS into an virtual env.

