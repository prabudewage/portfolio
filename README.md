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

- Led data collection, processing, and analysis of 53 atmospheric variables from in-situ and remote sensing data utilizing Linux HPC clusters to fit and validate empirical machine learning models for predicting nationwide Particulate Matter concentration with 85% accuracy. 
- This diverse array of predictor variables included high-temporal AOD data derived from the GOES-16 geostationary satellite, meteorological variables sourced from the ECMWF, ancillary data gathered from various external sources, location-specific solar angles, and reanalysis data related to AOD and air pollutant gases, obtained from the MERRA-2 database.
- These variables originate from disparate sources, each characterized by distinct coordinate systems and temporal resolutions, requiring the use of a linear interpolation method to generate aligned datasets.

![Model Evaluation](/assets/pm_est_eval.png)

![PM Estimation Reconstruction Map](/assets/pm_est_map.png)

### Humidity Correction for Low-Cost PM sensor
- Most low-cost Particulate Matter (PM) sensors lack an integrated particle drying mechanism, leading to an overestimation of particulate matter concentration under high humidity conditions.
- This project involved development of a humidity correction algorithm by integrating insights from hygroscopic growth theories and employing the frequency polygon method, analogous to the particle size distribution.

![Hygroscopic Growth](/assets/hydro_grow.png)

![Frequency Polygon](/assets/frq_poly.png)

- The results revealed favorable agreement between the corrected low-cost Particulate Matter (PM) sensors measurements and the data from the EPA reference sensor.



### Estimate Airborne Nanoparticle concentration

- Despite the minute mass concentration of ultra particles (with a diameter less than 100 nm), they dominate the particle count in the atmosphere.
- Typically originating from engine emissions, these ultrafine particles prevail in particle count in urban areas. Their smaller size compared to other particles facilitates easy penetration through the human respiratory system, depositing in the lungs.
- Many commercially available low-cost particulate matter sensors have limitations in their measurements.
- Introduced a computational method utilizing the aerosol size distribution with three log-normal distributions representing nuclei, accumulation, and coarse modes enables the calculation of the particle count with a diameter less than 50 nm. 


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
