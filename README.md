# Data Scientist

#### Technical Skills: Python, SQL, Excel, MATLAB, GitHub, HPC

## Education
- Ph.D., Physics | The University of Texas at Dallas (_May 2024_)								       		
- M.S., Physics	| The University of Texas at Dallas (_December 2020_)	 			        		

## Experience
**Graduate Research Assistant (_June 2021 - Present_)**
- Over the course of my current research, I have gained both experimental and data analysis skills as an experimental physicist.
- I am quite familiar with programming languages such as Python, MATLAB, and Julia and I have been conducting several projects which includs data analysis and building - emperical machine learning models in python. 
- My work also included extensive big data analysis, interpolation, synchronization, automation, visualization and identification of potential variables for machine learning models utilizing Linux High-Performance Computing (HPC) clusters. 
- I have accumulated over two years of hands-on experience in atmospherics, environmental and remote sensing data analysis.
- Developing physics-based computational algorithm models.
- Preparing manuscripts for my PhD research dissertation and academic publications. 



## Projects
### Estimation of Particlulate Matter Concentration in United States
<!--[Publication](https://www.mdpi.com/1424-8220/22/8/3048) -->
In the development of nationwide PM$_{2.5}$ models, a diverse array of predictor variables was harnessed.
This included high-temporal AOD data derived from the GOES-16 geostationary satellite, meteorological variables sourced from the ECMWF, ancillary data gathered from various external sources, location-specific solar angles, and reanalysis data related to AOD and air pollutant gases, obtained from the MERRA-2 database. 
these variables originate from disparate sources, each characterized by distinct coordinate systems and temporal resolutions. To align these datasets, a linear interpolation method was applied, albeit with noticeable consequences on model performance.
In particular, among the most influential variables that contributed to this performance were AOD, specific humidity, dew point temperature, carbon monoxide, and carbon dioxide.

- Led data collection, processing, and analysis of 53 atmospheric variables from in-situ and remote sensing data utilizing Linux HPC clusters to fit and validate empirical machine learning models for predicting Particulate Matter concentration with 85% accuracy.
- Developed a physics-based algorithm for humidity correction in Particulate Matter concentration for commercially available low-cost sensors that do not incorporate a dry mechanism. This improvement increased the accuracy of data by 5% in R2 value.
- Introduced a computational method to estimate airbone nanoparticle (diameter < 50 nm) count in atmosphere. 

Developed emperical machine learning model in python using 53 climate and remote sensing variables to estimate Praticulate Matter in United States.

![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)

### Humidity Correction for Low-Cost PM sensor

Most of the low-cost Particulate Matter (PM) sensors currently available in the market lack an integrated particle drying mechanism. In environments characterized by elevated relative humidity, particulate matter can experience hygroscopic growth, leading to overestimation of particle sizes by commercially available low-cost PM sensors under such weather conditions. 
we have developed a humidity correction algorithm by integrating insights from a previous study \cite{DiAntonio:2018} and employing the frequency polygon method, analogous to the particle size distribution.
The results revealed favorable agreement between the corrected IPS7100 measurements and the data from the EPA reference sensor.

Used python to developed humidity correction algorithm based on physics theories for low-cost PM sensor to accuratly measure the PM concentration under high humidity condition.

### Estimate Airborne Nanoparticle concentration
Despite the minute mass concentration of ultrafine particles (with a diameter less than 100 nm), they dominate the particle count in the atmosphere.
Typically originating from engine emissions, these ultrafine particles prevail in particle count in urban areas. Their smaller size compared to other particles facilitates easy penetration through the human respiratory system, depositing in the lungs.
Many commercially available low-cost particulate matter sensors have limitations in their measurements.
PM$_{0.1}$ and PC$_{0.1}$ measurements from these sensors exclude the count of particles with diameter less than 50 nm. Using the aerosol size distribution with three log-normal distributions representing nuclei, accumulation, and coarse modes enables the calculation of the particle count with a diameter less than 50 nm. This method proves to be valuable for characterizing PM and PC across all size fractions in various geographical areas.

Introducing computational algorithm based on physics theories to estimate airborne nano particle concentration.

### Respiratory Disorders Classification

Developed empirical machine learning models that can classify 6 respiratory disorders based on data from respiratory sound and demographic information with fast Fourier transform using MATLAB. 

## Awards

- Graduate Studies Scholarship, The University of Texas at Dallas, 2019
- Annual Householder Award - Outstanding MS Academic Achievement, The University of Akron, 2018 & 2017


![Bike Study](/assets/img/bike_study.jpeg)

## Talks
- Audio Recording to Detect Respiratory Diseases - Scientific Computing (PHYS 5315), Fall 2020
- Glass Classification Using Machine Learning- Big Data and Machine Learning for Scientific Discovery (PHYS 5336), Spring 2019

<!--- [Data Science YouTube](https://www.youtube.com/channel/UCa9gErQ9AE5jT2DZLjXBIdA) -->

## Publications
1. Prabuddha Madusanka, Lakitha Wijeratne, Xiaohe Yu, Mazhar Iqbal, Gokul Balagopal, John Waczak, Ashen Fernando, Shisir Ruwali and David J. Lary, Providing Estimates of Airborne Particulate Matter Utilizing Complimentary In-Situ and Remote Sensing Approaches (In preparation)

<!-- - [Data Science Blog](https://medium.com/@shawhin)-->
