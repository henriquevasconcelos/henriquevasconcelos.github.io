# Portfolio

---

## UVCS

<img src="images/uvcs_intro.png?raw=true" width="1250"/>

UVCS is a project in development aiming to map and model pathogens under UV-C light to combat hospital infections. This map is continuously updated, informing our robot TALOS, how much time it should devote to each location to ensure a safe and thorough sanitation. It also aims to develop a web app where hospital managers can track how sanitized each point of each environment is, how many times has each space been sanitized and how much time is needed to clean it. The project was highlighted as the best Ideation Team in the 2020/2021 Entrepreneurial Initiation Program at UFRGS.

I was the main developer of the embedded model, which was based on the works of [Walker and Ko](https://pubs.acs.org/doi/10.1021/es070056u), [Sabino et al](https://www.sciencedirect.com/science/article/abs/pii/S1572100020303495?via%3Dihub) and many others. The implementation was initially done in Python but later we switched to Julia for increased performance. In the system's current iteration, we estimate a 99% reduction of the pathogens in the room in under one minute.

## Pampa Aerodesign 

### Pampa Propeller Data Set

<img src="images/ppds_logo.png?raw=true"/>

[Pampa Propeller Data Set](https://github.com/Pampa-Aerodesign/PampaPropellerDS) or PPDS, provides dynamic performance data for all propellers made by [APC](https://www.apcprop.com/), in a analysis-friendly format, with propeller and RPM indexation. It enables the continuous update of this data from the latest files provided by APC via a Python Crawler and regex formater.

**Features in development**
- A Streamlit app to visualize data from the propeller database;
- Incorporating unit conversion with [Pint](https://pint.readthedocs.io/en/stable/);
- Local indexing of the dataset using [TinyDB's](https://tinydb.readthedocs.io/en/latest/) JSON database;

**Analysis**

I have also [analysed](pdf/propeller_analysis.html) the propellers the team currently owns, using [Pandas](https://pandas.pydata.org/) and [Matplotlib](https://matplotlib.org/) to visualise their performance.

<img src="images/ppds_plots.png?raw=true"/>

---

### Airfoil Optimization
The team had the task of improving the performance of it's airfoil, to do so we employed a genetic algorithm written in Fortran aiming to maximize
the lift coeficient (CL) whilst maintaining a minimum thickness and a maximum drag coefficient. The computational costs of these simulations was too high and so 
I employed Google Cloud's elastic computation service, thereby reducing the execution time by a factor of 10. I subsequently also analyzed the performance of the resulting airfoil, which had a 10% higher CL while holding to the stated optimization constraints.

<img src="images/Airfoil.png?raw=true"/>

