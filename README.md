# Analysis_Reports
This repo contains data analysis/research reports I've written for various undergraduate, research internship, and postgraduate projects.

This includes:

1) [BirdSnackPaper](https://arxiv.org/search/?searchtype=author&query=Ward%2C+S+M) (2022/23); ***B***ayesian ***I***nference of ***R***v ***D***istributions using ***S***uper***N***ova ***A***pparent ***C***olours at pea***K***. A modular pipeline to interpolate spatio-temporal data with **2D Gaussian processes**, and feed the resulting measurements into a **Hierarchical Bayesian Model** to infer population hyperparameters (and distentangle intrinsic and extrinsic effects). This work was published in *MNRAS*. See also [Bird-Snack](https://github.com/sam-m-ward/birdsnack/tree/main) repo.

2) [SupernovaSiblingsPaper](https://ui.adsabs.harvard.edu/abs/2022arXiv220910558W/abstract) (2021-23); **Hierarchical Bayesian analysis** of Type Ia supernovae that exploded in the same host galaxy: 'Supernova Siblings'. Research undertaken as part of the [Young Supernova Experiment](https://yse.ucsc.edu), an international collobaration of astronomers and data scientists. This work was published in *The Astrophysical Journal*, and was nominated for [**Best Student-led Astrostatics Paper of 2022**](http://astrostat.org/competition/). See also [Supernova-Siblings](https://github.com/sam-m-ward/Supernova-Siblings) repo.

<!--- 3) [PhD1stYearReport.pdf](https://github.com/sam-m-ward/Analysis_Reports/blob/main/PhD1stYearReport.pdf) (2020/21); Various PhD mini-projects undertaken during my first year, including: **Gaussian process interpolation of time-series, Hierarchical Bayesian Inference in Stan, and big-data grid search for parameter correlations**. GP-regression involved fitting Foundation DR1 data to extract features across ~100's of supernova light curves. I used these features to infer populations trends, by performing hierarchical linear regression in a probabilistic programming language called Stan. I also searched for correlations between these light curve features and the measured ejecta velocity, doing a grid search and computing p-values to determine detection significance. --->

3) [MastersThesis.pdf](https://github.com/sam-m-ward/Analysis_Reports/blob/main/MastersThesis.pdf) (2019/20); Masters project goal was to **search for correlations and measure time lags between multiple sets of time-series data**. I created gamma-ray light curves of accreting supermassive black holes using the all-sky Fermi Gamma-ray Space Telescope. I then used Discrete Cross Correlation Functions (DCCF's) to search for correlations with the radio light curves from the Sub-Millimetre Array. Finally, I exploited Monte Carlo light curve simulations using the Emmanoulopoulos 2013 framework to **compute confidence intervals, and thus measure the significance of inferred time lags**. See also [Time-Lag-Analysis](https://github.com/sam-m-ward/Time-Lag-Analysis) repo.

4) [BScReport.pdf](https://github.com/sam-m-ward/Analysis_Reports/blob/main/BScReport.pdf) (2018/19); BSc project involved **Fourier analysis to fit time-series data** of a pulsating star, measure the properties of a long-term modulation function, and infer physical properties like star temperature and radius. I used a telescope on the roof of the Durham physics department to measure (B,V) time-series data; I fitted the resulting photometry using a Fourier series, and inferred the sine-wave parameters that characterised the long-term evolution or 'Blazhko Modulation'. See also [Pulsating-Variable-Star](https://github.com/sam-m-ward/Pulsating-Variable-Star) repo.

5) [UTokyoReport.pdf](https://github.com/sam-m-ward/Analysis_Reports/blob/main/UTokyoReport.pdf) (2018); University of Tokyo Research Internship project used **Monte Carlo numerical simulations** to investigate the effect of stellar flybys on resonant planetary systems. I built fake planetary systems using the AMUSE software, sent in a rogue star with a random trajectory and velocity, and measured the effect on the planets' orbital periods and semi-major axes.
