# Portfolio

---

## Pampa Aerodesign 

### Pampa Propeller Data Set
[Pampa Propeller Data Set](https://github.com/Pampa-Aerodesign/PampaPropellerDS) or PPDS, provides dynamic performance data for all propellers made by [APC](https://www.apcprop.com/), in a analysis-friendly CSV format, separated by propeller and RPM. It enables the continuous update of the data from the latest files provided by APC via a Python Crawler and regex formater. 

**Features in development**
- A Streamlit app to visualize data from the propeller database;
- Incorporating unit conversion with [Pint](https://pint.readthedocs.io/en/stable/);
- A local index of the dataset using [TinyDB's](https://tinydb.readthedocs.io/en/latest/) JSON database;

<img src="images/PPDS_fig.png?raw=true"/>

---

### Airfoil Optimization
The team had the task of improving the performance of it's airfoil, to do so we employed a genetic algorithm written in Fortran aiming to maximize
the lift coeficient (CL) whilst maintaining a minimum thickness and a maximum drag coefficient. The computational costs of these simulations was too high and so 
I employed Google Cloud's elastic computation service reducing the execution time by a factor of 10. I subsequently also analyzed the performance and plotted the resulting airfoil, which had a 10% higher CL while holding to the stated optimization constraints.

<img src="images/Airfoil.png?raw=true"/>

---

### MTOW



