# summa_snow_unloading_analysis
## Repo for python notebooks that analyize multiple canopy-snow unloading parameterizations in pySUMMA

*Created by:* Cassie A Lumbrazo (lumbraca@uw.edu) \
*Last edited:* January 2022 \
*Program Language:* Python 

---

This repo is created to host analysis related to manuscript 2021WR030852 submitted to AGU WRR, 

### Evaluating multiple canopy-snow unloading parameterizations in SUMMA with time-lapse photography characterized by citizen scientists 
**Cassie Lumbrazo[^1]**, Andrew Bennett[^1], William Ryan Currier[^2], Bart Nijssen[^1], Jessica Lundquist[^1] 

[1] Department of Civil Engineering, University of Washington, Seattle, WA

[2] National OCeanic and Atmospheric Administration, Earth Systen Research Laboratory, Physical Science Laboratory, Boulder, CO, USA


[^1]:Department of Civil Engineering, University of Washington, Seattle, WA
[^2]:National OCeanic and Atmospheric Administration, Earth Systen Research Laboratory, Physical Science Laboratory, Boulder, CO, USA

---

**Manuscript Main Points**
* Remote time-lapse cameras and citizen science shed light on forest-snow interception processes that are often overlooked.
* Site specific interception patterns, such as wind dominated unloading and riming, impact the transferability of unloading parameteriztions 
* The choice of unloading shceme impacts the canopy albedo feedback, and the partitioning of snow on the ground vs canopy-sublimation

---

## Table 1 (adapted): Canopy-snow unloading parameterizations

| Unloading Scheme Citation  | Paramertization Unloading Process                              | Paper NickName    | Python Notebook Nickname |
|----------------------------|----------------------------------------------------------------|-------------------|--------------------------|
| [Andreadis et al. (2009)](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2008WR007042)    | Ratio of solid snow in canopy unloads in presence of meltwater | Melt              | melt                     |
| [Hedstrom & Pomeroy, (1998)](https://onlinelibrary.wiley.com/doi/abs/10.1002/%28SICI%291099-1085%28199808/09%2912%3A10/11%3C1611%3A%3AAID-HYP684%3E3.0.CO%3B2-4) | Time dependent exponential decay unloading                     | Exponential-Decay | exp, dexp   (d: default) |
| Roesch et al. (2001)       | Wind and temperature dependent unloading                       | Wind-Temperature  | wind, dwind (d: default) |


---




