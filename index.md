# Portfolio

---

## UVCS

<img src="images/uvcs_intro.png?raw=true" width="1250"/>

UVCS is a project in development aiming to map and model pathogens under UV-C light so as to combat hospital infections. This map is continuously updated, informing our robot TALOS, how much time it should devote to each location to ensure safe and thorough sanitation.

I was the main developer of the embeded model, using the work of [Walker and Ko](https://pubs.acs.org/doi/10.1021/es070056u). The model was inplemented initially in Python and then in Julia for increased performance. In the system's current iteration, we estimate a 99% reduction of the pathogens in the room in under one minute.

## Pampa Aerodesign 

### Pampa Propeller Data Set

<img src="images/ppds_logo.png?raw=true"/>

[Pampa Propeller Data Set](https://github.com/Pampa-Aerodesign/PampaPropellerDS) or PPDS, provides dynamic performance data for all propellers made by [APC](https://www.apcprop.com/), in a analysis-friendly CSV format, sorted by propeller and RPM. It enables the continuous update this data from the latest files provided by APC via a Python Crawler and regex formater. 

**Features in development**
- A Streamlit app to visualize data from the propeller database;
- Incorporating unit conversion with [Pint](https://pint.readthedocs.io/en/stable/);
- A local index of the dataset using [TinyDB's](https://tinydb.readthedocs.io/en/latest/) JSON database;

**Analysis**

I have also [analysed](pdf/propeller_analysis.html) the propellers the team currently owns, using [Pandas](https://pandas.pydata.org/) and [Matplotlib](https://matplotlib.org/) to visualise their performance and select the best one for use. 

<img src="images/ppds_plots.png?raw=true"/>

---

### Airfoil Optimization
The team had the task of improving the performance of it's airfoil, to do so we employed a genetic algorithm written in Fortran aiming to maximize
the lift coeficient (CL) whilst maintaining a minimum thickness and a maximum drag coefficient. The computational costs of these simulations was too high and so 
I employed Google Cloud's elastic computation service reducing the execution time by a factor of 10. I subsequently also analyzed the performance and plotted the resulting airfoil, which had a 10% higher CL while holding to the stated optimization constraints.

<img src="images/Airfoil.png?raw=true"/>

