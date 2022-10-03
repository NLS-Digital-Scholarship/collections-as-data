# collections-as-data
Data analysis of NLS [collections as data](https://cerlblog.wordpress.com/2020/08/13/special-collections-as-data-the-national-library-of-scotlands-data-foundry/), including collections of metadata and digitised text.  Visit the National Library of Scotland's [Data Foundry > Tools > Jupyter Notebooks](https://data.nls.uk/tools/jupyter-notebooks/) to learn more about the contents of each Notebook and the data it explores.

To explore the collections listed below in live Jupyter Notebooks, [open them here in Binder](https://notebooks.gesis.org/binder/v2/gh/NLS-Digital-Scholarship/collections-as-data/8314a1825cc36c358854db206b3a4073acd41921) (please note this may take several minutes to load).

To copy and work with the Jupyter Notebooks on your own machine, see [Setup](#setup).

### Table of Contents
* [Overview](#overview)
* [Datasets](#datasets)
* [Setup](#setup)
* [Suggested Citations](#suggested-citations)

## Overview

### About
This repository explores datasets from the National Library of Scotland's [Data Foundry](https://data.nls.uk/) using Jupyter Notebooks.  The Notebooks provide introductions to NLS collection data suitable for those with or without experience programming.  For an introduction to using Jupyter Notebooks, please refer to [Tim Sherratt's GLAM Workbench](https://glam-workbench.github.io/getting-started/).

### References
While creating the Jupyter Notebooks in this repository, the author referenced material from the sources below.  The author sought to use the material for learning only, applying code taught in the material to NLS collections and inform the explanations of the code, but not copy the code or code explanations. If you feel the citations below (and in each Noteook) do not provide adequate attribution for your work, please contact digital.scholarship@nls.uk.
* Alex, Beatrice and Llewellyn, Clare. (2020) *Library Carpentry: Text & Data Mining*. Centre for Data, Culture & Society, University of Edinburgh. http://librarycarpentry.org/lc-tdm/.
* Bird, Steven and Klein, Ewan and Loper, Edward. (2019) *Natural Language Processing with Python – Analyzing Text with the Natural Language Toolkit*.  O'Reilly Media. 978-0-596-51649-9. https://www.nltk.org/book/.
* Python Software Foundation. (2020) *xml.etree.ElementTree — The ElementTree XML API*. Python 3.8.6 Documentation, The Python Standard Library, Structured Markup Processing Tools. https://docs.python.org/3/library/xml.etree.elementtree.html.

## Datasets

### Collection 1: Britain and UK Handbooks
Explore this collection in a static or interactive Jupyter Notebook [here](https://data.nls.uk/tools/jupyter-notebooks/exploring-britain-and-uk-handbooks/)
* Owner: National Library of Scotland
* Creator: National Library of Scotland
* DOI: https://doi.org/10.34812/8pje-tv48
* Date created: 10/01/2019
* Rights: Items in this dataset up to 1968 are free of known copyright and in the public domain. Items in this dataset from 1969 are available under the [Open Government License v.3.0](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/).
* Contact: digital.scholarship@nls.uk

### Collection 2: A Medical History of British India
Explore this collection in a static or interactive Jupyter Notebook [here](https://data.nls.uk/tools/jupyter-notebooks/exploring-a-medical-history-of-british-india/)
* Owner: National Library of Scotland
* Creator: National Library of Scotland
* DOI: https://doi.org/10.34812/2w0t-3f08
* Date created: 27/08/2019
* Rights: Items in this dataset are free of known copyright and in the public domain.
* Contact: digital.scholarship@nls.uk

### Collection 3: Edinburgh Ladies' Debating Society
Explore this collection in a static or interactive Jupyter Notebook [here](https://data.nls.uk/tools/jupyter-notebooks/exploring-edinburgh-ladies-debating-society/).
* Owner: National Library of Scotland
* Creator: National Library of Scotland
* DOI: https://doi.org/10.34812/rqn6-dm40
* Date created: 15/10/2019
* Rights: Items in this dataset are likely to be free of known copyright restrictions ([No Known Copyright](https://rightsstatements.org/page/NKC/1.0/?language=en)).
* Contact: digital.scholarship@nls.uk

### Collection 4: Lewis Grassic Gibbon First Editions
Explore this collection in a static or interactive Jupyter Notebook [here](https://data.nls.uk/tools/jupyter-notebooks/exploring-lewis-grassic-gibbon-first-editions/).
* Owner: National Library of Scotland
* Creator: National Library of Scotland
* DOI: https://doi.org/10.34812/a61z-m825
* Date created: 15/10/2019
* Rights: Items in this dataset are free of known copyright and in the public domain.
* Contact: digital.scholarship@nls.uk

### Collection 5: The National Bibliography of Scotland (version 1)
Explore this collection in a static or interactive Jupyter Notebook [here](https://data.nls.uk/tools/jupyter-notebooks/exploring-the-national-bibliography-of-scotland/).
* Owner: National Library of Scotland
* Creator: National Library of Scotland
* Website: Visit the [NLS Data Foundry](https://data.nls.uk/data/metadata-collections/national-bibliography-of-scotland/)
* Date created: 30/08/2019
* Date updated: 06/09/2019
* Licence: Creative Commons Attribution 4.0 International ([CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/))

## Setup

To clone the Git repository and run the Jupyter Notebooks on your own machine, follow the steps below according to your operating system. 

**For Mac and Linux:**

```
# Install (if not yet installed) the Python venv (virtual environment) module
python3 -m pip install --user virtualenv

# Create a virtual environment (you can change 'env' to a name of your choice)
python3 -m venv env

# Activate the environment
source env/bin/activate

# Clone the repository
git clone https://github.com/NLS-Digital-Scholarship/collections-as-data.git

# Enter and initialize the repository
cd collections-as-data
git init

# Install the required packages
python3 -m pip install -r requirements.txt

# When you're finished, deactivate the environment (simply activate it once
# more and enter the repository if when you wish to resume your work)
deactivate
```

**For Windows:**

```
# Install (if not yet installed) the Python venv (virtual environment) module
py -m pip install --user virtualenv

# Create a virtual environment (you can change 'env' to a name of your choice)
py -m venv env

# Activate the environment
.\env\Scripts\activate

# Clone the repository
git clone https://github.com/NLS-Digital-Scholarship/collections-as-data.git

# Enter and initialize the repository
cd collections-as-data
git init

# Install the required packages
py -m pip install -r requirements.txt

# When you're finished, deactivate the environment (simply activate it once
# more and enter the repository if when you wish to resume your work)
deactivate
```

For additional guidance on Python virtual environments with pip, please visit [Installing packages using pip and virtual environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/).

## Suggested Citations

If you find any of these Notebooks useful in your work, we would appreciate your citation of them.  Suggested citations for each Notebook are:

* National Library of Scotland. *Exploring A Medical History of British India.* National Library of Scotland, 2020. https://doi.org/10.34812/k2c4-7a56
* National Library of Scotland. *Exploring Lewis Grassic Gibbon First Editions.* National Library of Scotland, 2020. https://doi.org/10.34812/gq6w-6e91
* National Library of Scotland. *Exploring The National Bibliography of Scotland.* National Library of Scotland, 2020. https://doi.org/10.34812/an7d-xk61
* National Library of Scotland. *Exploring Britain and UK Handbooks.* National Library of Scotland, 2020. https://doi.org/10.34812/ex5e-rs36
* National Library of Scotland. *Exploring Edinburgh Ladies’ Debating Society.* National Library of Scotland, 2020. https://doi.org/10.34812/0d3w-zt02
