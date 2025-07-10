# Portfolio

---

## Deepki

<img src="images/deepki_intro.png?raw=true" width="1250"/>


[Deepki](https://deepki.com/) is the world's largest Climate Tech in the real estate sector, which represents 20-30% of global emissions ([IPCC 2019](https://www.ipcc.ch/report/ar6/wg3/chapter/chapter-9/)). The company helps its clients design, track and implement its decarbonization plans for the 1.6 million buildings it manages in over 69 countries. I began at Deepki as part of my end of Master's project and was subsequently hired full-time as a Customer Solutions Engineer, where I translate the needs of Deepki's largest clients into technical solutions and lead internal R&D projects.

In my full-time role, I've taken on increasingly complex projects and leadership responsibilities. I served as Lead CSE for [Pictet]([url](https://www.pictet.com/ch/en/about)), a new UK/Swiss owner real estate client, managing the complete project lifecycle from initial platform setup and client kickoff to developing custom exports and adapting our SFDR/Taxonomy module to meet their specific regulatory requirements. For Real IS, I led a comprehensive platform standardization initiative, refactoring existing exports and implementing a robust schema evolution system while establishing the alerts/monitoring module to improve platform reliability. I also inherited RIVP (Régie Immobilière de la Ville de Paris), a legacy client platform with critical stability issues and daily workflow failures. Through systematic platform standardization efforts, I increased the stability score by 20% and significantly reduced daily incidents, transforming a problematic legacy system into a reliable platform.

Beyond client work, I've tackled major operational challenges within Deepki itself. The billing team faced 8-month billing cycles due to complex client structures and lack of visibility into which buildings were in the platform. I developed a comprehensive billing feature that manages building-specific pricing, enables price assignment to buildings, and exports billing data for invoice generation. This system has been deployed to Deepki's largest clients and is expected to process approximately 30M Euros of ARR in Q4 2025 - Q1 2026.

Another significant challenge was managing context across Deepki's 400+ projects, where documentation was scattered across Google Drive, Confluence, and technical manuals. I led the development of a secure, centralized knowledge management system by forking Onyx, an open-source RAG pipeline framework. The solution indexes all documentation through custom connectors, stores data in Vespa DB using Neomic Embedding models, and provides secure LLM chat capabilities via AWS Bedrock. This project established a strong partnership with Amazon and serves consultants, CSEs, and sales teams across the organization. I was responsible for deployment, adaptation, custom assistant creation, and ongoing technical maintenance.

During my initial internship period, I worked extensively with major clients including [Amundi](https://int.media.amundi.com/real-estate.html) and [Art-Invest](https://www.art-invest.de/en/), both large [REITs](https://en.wikipedia.org/wiki/Real_estate_investment_trust). For Amundi, I updated carbon emissions pathways to align with [CRREM v2](https://www.crrem.org/about-crrem-phase-ii/) standards, developed custom exports for their AltoRE fund, and resolved critical energy data collection bugs. With Art-Invest, I led initial platform setup and implemented tailored risk assessment and alerts panels. I also developed the Compare Collections app, a transverse tool that reduced testing time for different methodologies from weeks to hours, and created specialized ESG forms and management panels for various clients including Atream's CARAC fund and Real IS.

Throughout my tenure, I've utilized Python for data analysis, and ETL processes, managed databases with MongoDB, leveraged AWS services for cloud infrastructure, and created interactive tools using Streamlit and pandas. More recently I've been focusing on RAG pipelines, embedding models, and secure LLM deployment frameworks (AWS bedrock, self-hosted).


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

