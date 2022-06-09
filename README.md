# 2022_NISO

These are the notebooks used for my presentation at the NISO Training Serieos on [Working with Scholarly APIs](https://www.niso.org/events/working-scholarly-apis-niso-training-series). 

# Methods and Tools for Scholarly Data Analytics - Thursday, June 9, 2022
When working with scholarly data, the analyst must consider many different technology aspects. In terms of data integration, knowledge of the available datasets and how to link across them is crucial. For effective data enrichment, experience with widely used libraries and APIs can add additional value to the data. Finally, visualization of the outcomes is essential for proper interpretation and communication of findings.
 
For this presentation, I will demonstrate several technology solutions relating to these import steps showing how Python, open-source libraries and public data sources can be used effectively for custom analysis. In particular, topic modelling and geoparsing will be discussed, along with network visualization using Gephi.

# Requirements

## Python
The code were developed using python 3.9.8.

Use: ``pip install -r requirements.txt`` to install the revelant dependencies.

Start jupyter-lab using the command ``jupyter-lab``

# Geoparser
The notebook 02 Geoparse.ipynb relies on the Edinburgh Geoparser to find locations mentioned in the title & abstract.

See [https://www.ltg.ed.ac.uk/software/geoparser/](https://www.ltg.ed.ac.uk/software/geoparser/)

You must download the package and place in the working directory in a folder called geoparser-1.2 (or update the code accordinly to locate the binary)