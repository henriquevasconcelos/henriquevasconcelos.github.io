# Portfolio

---

## Deepki

<img src="images/deepki_intro.png?raw=true" width="1250"/>

<i>Paris, France | Feb 2024 - Aug 2024</i>

[Deepki](https://deepki.com/) is the world's largest Climate Tech in the real estate sector, which represents 20-30% of global emissions ([IPCC 2019](https://www.ipcc.ch/report/ar6/wg3/chapter/chapter-9/)). The company helps its clients design, track and implement its decarbonization plans for the 1.6 million buildings it manages in over 69 countries. I worked at Deepki as part of my end of Master's project. As a Customer Solutions Engineer intern, my primary objective was to translate the needs of  Deepki's largest clients into technical solutions. This meant customizing the various modules of the Deepki Ready platform for each client. We did this by working with Deepki's ESG consultants to define the client's needs and draw a platform roadmap for that project. We also interfaced with the product and development teams to improve the platform itself, and also develop internal tools to help us service the roughly 500 different projects we had to manage.

During my internship, I spent a lot of my time with two major clients, [Amundi](https://int.media.amundi.com/real-estate.html) and [Art-Invest](https://www.art-invest.de/en/), both large [REITs](https://en.wikipedia.org/wiki/Real_estate_investment_trust). For Amundi, I updated their carbon emissions pathways to align with the latest [CRREM v2](https://www.crrem.org/about-crrem-phase-ii/) standards, developed custom exports for their AltoRE fund, and resolved critical energy data collection bugs. With Art-Invest, I led the initial platform setup for their portfolio, demoing it for the client. I also implemented tailored risk assessment and alerts panels.

I also did many one-shot implementation tasks, including the creation of specialized ESG forms for Atream's CARAC fund and the development of a comprehensive Mandate Management Panel for Real IS. These projects helped me develop my ability to quickly assess client requirements and deliver targeted solutions under short time frames (< 4 weeks). I was also responsible for the development of the Compare Collections app. This was a transverse task that allowed fellow CSEs to compare data across AWS environments. The app reduced the time it took for to test different methodologies from about a week to a couple of hours.

To accomplish these tasks, I utilized a diverse set of tools and technologies. I worked extensively with Python for scripting, data analysis, and ETL processes, and used MongoDB for database management. I employed AWS services for cloud infrastructure management and leveraged Streamlit and pandas for creating interactive data visualization tools. My role also involved working with YAML configurations, Git for version control, and various data processing and reporting frameworks specific to the Deepki platform.

## AérOnde

<img src="images/aeronde_intro.png?raw=true" width="1250"/>

<i>Grenoble, France | Feb 2023 - Sep 2023</i>

During my time at AérOnde, I contributed to the development of a pressurization system for an electric Vertical Takeoff and Landing (eVTOL) aircraft. My primary focus was on the Minimal Flyable Pressurization System (MFPS) to be used in the initial version of the vehicle and a conceptual exploration for the Mark 1 system.

For the MFPS, I helped define system requirements for both stationary and in-flight scenarios. I selected and characterized a fixed static pressure fan crucial for envelope integrity, and conducted tests on fuse protection and battery autonomy. I designed and built the first 10-20 versions of the system, and later also helped with ground testing. As of Sep/2024, The system is still used  in crewed flights.

In the Mark 1 conceptual phase, I contributed to architectural decisions, advocating for a triple independent module design to enhance reliability. I performed flow rate and valve dimensioning calculations based on operational requirements and explored linear actuator concepts for valve control.

To do these tasks, I used a range of tools. In the design phase we used Autodesk's Fusion360 for the CAD designs, Jupyter Notebooks for most of the modelling and the calculations. For the prototyping we had access to laser cutters, 3D printers, milling machines, hand drills, etc.

<img src="images/aeronde_close.png?raw=true" width="1250"/>

## Jusbrasil

<img src="images/jusbrasil_intro.png?raw=true" width="1250"/>

<i>Remote, Brazil | Sep 2021 - Sep 2022</i>

At Jusbrasil, I played a key role in maintaining and evolving the company's data platform. Our team undertook a complete refactoring of the platform, transforming it into a cloud data-lake capable of processing terabytes of data monthly. The project used then cutting-edge technologies including Kafka, BigQuery, Apache Spark, and a suite of custom-built tools.

The refactored platform significantly enhanced Jusbrasil's data processing capabilities, enabling more efficient extraction, loading, and transformation of large-scale datasets. This improvement directly contributed to the company's ability to handle and analyze vast amounts of legal information, supporting its mission to make legal processes more accessible and transparent.

In addition to my core data engineering responsibilities, I gained valuable experience in DevOps practices. This included operating a Kubernetes cluster, managing infrastructure through Terraform, and implementing CI/CD pipelines. These skills were crucial in ensuring the reliability and scalability of our data platform.

## UVCS

<img src="images/uvcs_intro.png?raw=true" width="1250"/>

<i>Remote, Brazil | Aug 2020 - Sep 2021</i>

UVCS was a project in development aiming to map and model pathogens under UV-C light to combat hospital infections. This map is continuously updated, informing our robot TALOS, how much time it should devote to each location to ensure a safe and thorough sanitation. It also aims to develop a web app where hospital managers can track how sanitized each point of each environment is, how many times has each space been sanitized and how much time is needed to clean it. The project won Best Team in the 2020/2021 Entrepreneurial Initiation Program selected by UFRGS and the Chamber of Industry (Senai RS).

I was the main developer of the embedded model, which was based on the works of [Walker and Ko](https://pubs.acs.org/doi/10.1021/es070056u), [Sabino et al](https://www.sciencedirect.com/science/article/abs/pii/S1572100020303495?via%3Dihub) and many others. The implementation was initially done in Python but later we switched to Julia for increased performance. In the system's current iteration, we estimate a 99% reduction of the pathogens in the room in under one minute.

## Pampa Aerodesign 

<i>Porto Alegre (RS), Brazil | Oct 2019 - Dec 2021</i>

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

