# cloud-cover-estimation

Juypter scripts which present methods for cloud cover estimation (see CloudCover.ipynb and MultipleThreshold.ipynb) 

### CloudCover.ipynb
Daytime method uses a simple pixel red-blue ratio approach. The daytime implementation needs some improvement - the very bright areas around the sun are sometimes identified as clouds leading to cloud cover overestimation. Ideally a solar would be applied.

- Lothon, M., Barnéoud, P., Gabella, O., Lohou, F., Derrien, S., Rondi, S., Chiriaco, M., Bastin, S., Dupont, J.-C., Haeffelin, M., Badosa, J., Pascal, N., and Montoux, N.: ELIFAN, an algorithm for the estimation of cloud cover from sky imagers, Atmos. Meas. Tech., 12, 5519–5534, https://doi.org/10.5194/amt-12-5519-2019, 2019

Two methods for night cloud estimation are also included (for night skies with moon and without). 

- Gao, B.; Ping, Y.; Lu, Y.; Zhang, C. Nighttime Cloud Cover Estimation Method at the Saishiteng 3850 m Site. Universe 2022, 8, 538. https://doi.org/10.3390/universe8100538

### MultipleThreshold.ipynb 

Alternative approach using thresholding implemented from:

- Kazantzidis, Andreas & Tzoumanikas, Panagiotis & Bais, Alkiviadis & Fotopoulos, Spiros & Economou, George. (2012). Cloud Detection and Classification with the Use of Whole-Sky Ground-Based Images. Atmospheric Research. 113. 80-88. 10.1016/j.atmosres.2012.05.005. 


