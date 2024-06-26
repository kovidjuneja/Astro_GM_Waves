![Banner](https://github.com/kovidjuneja/assets/blob/main/Thebanner.jpg)

# Astro_GM_Waves 
[(Back to top)](#table-of-contents)

Astro_GM_Waves is a machine learning model designed to effectively analyze GM waves data.


## Table of Contents
- [Astro_GM_Waves](#astro_gm_waves)
- [Table of Contents](#table-of-contents)
- [Brief Overview](#brief-overview)
- [Data Sources](#data-sources)
- [History](#history)
- [Installation](#installation)
- [Theoretical Results](#theoretical-results)
- [Mathematical Results](#mathematical-results)
- [Conclusion](#conclusion)
## Brief Overview
[(Back to top)](#table-of-contents)

Einstein's theory of relativity suggested that accelerating masses emit gravitational waves. This fundamental concept is crucial in our project's goal of analyzing GM waves. We utilized LIGO data to study strain over time. Through a machine learning model, the project seeks to predict the merger time, total mass of the system emitting gravitational waves, identify the astronomical sources of these waves, estimate the distance of objects from Earth, and assess the expected data variations resulting from changes in mass.
## Data Sources
[(Back to top)](#table-of-contents)

To access the strain vs time data for LIGO, please visit:-
https://raw.githubusercontent.com/SAURABH-RAI1729/KRITIGW/main/GW150914_strain_data_final.txt
## History
[(Back to top)](#table-of-contents)

Before Einstein, it was proven that accelerated charged particles produce EM waves which interact strongly with matter, such as radio waves, X-rays, and light. Einstein believed that, similar to EM waves, accelerated masses should produce gravitational waves, which he proposed in his theory of relativity in 1915. These waves interact very weakly with matter, making their proof quite difficult. In 2015, LIGO made a breakthrough by proving the existence of gravitational waves, thus confirming Einstein's theory a century after its proposal.
 ## Installation
[(Back to top)](#table-of-contents)

Open Git Bash and change the directory to the location where the repository is to be cloned. Then, type the following commands.

```shell
  git init
```
```shell
  git clone https://github.com/kovidjuneja/Astro_GM_Waves
```
Now, install the requirements using the following command.

```shell
   pip install -r requirements.txt 
```
To access the code open the specific notebook using 

```shell
  jupyter notebook filename
```


    
##  Theoretical Results
[(Back to top)](#table-of-contents)

For viewing the results and evaluation, please visit:
 https://github.com/kovidjuneja/Astro_GM_Waves/blob/main/Barak_GW_Theoretical_part.pdf
## Mathematical Results
[(Back to top)](#table-of-contents)

#### Merger Time:- (-0.015869140625 s)

#### Chrip Mass Obtained:-  7.252531536305782e+31 kg(36.46320531073797 times the solar mass)

#### Total Mass Obtained:- Mtotal=2.3*Mchirp    (83.86537221469732 times the solar mass)

#### Mass of each of the bodies:- Mbody=Mtotal/2 (41.93268610734866 times the solar mass)

#### Distance between the bodies:- 443.3412701256073 km

#### Schwarzschild radius:- 123.87446155452152 km

#### Compactness Ratio:- 1.7894780916180903

#### Distance of the body from Earth:- 1.6360643629886842 billion light years



     For viewing the expected data of strain vs time for different sets of masses, visit:
https://github.com/kovidjuneja/Astro_GM_Waves/blob/main/Part_2_Drawing_Waveform.ipynb


## Conclusion
[(Back to top)](#table-of-contents)

### Given that the compactness ratio is less than 2, the objects in question are likely black holes. 
