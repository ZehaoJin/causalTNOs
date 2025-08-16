# causalTNOs

### [Paper: Causal evidence for the primordiality of colours in trans-Neptunian objects](https://doi.org/10.1093/mnrasl/slaf089)
### [1. Data](#1-data-1)
### [2. Code](#2-code-1)
### [3. Cite this work](#3-cite-this-work-1)

## 1. Data
Col-OSSOS: 229 TNOs [marsset_data_full.csv](https://github.com/ZehaoJin/causalTNOs/blob/main/marsset_data_full.csv)
- a : semimajor axis
- e : eccentricity
- inc : inclination
- c : spectral slope
- class2 : population class, `{'cen':'Centaurs','cla':'Classicals','det':'Detached','res':'Resonant','sca':'Scattered'}`

DES: 814 TNOs [DMSOnly__clipped.csv](https://github.com/ZehaoJin/causalTNOs/blob/main/DMSOnly__clipped.csv)
- a : semimajor axis
- e : eccentricity
- i : inclination
- c : spectral slope
- Class: population class.


## 2. Code
Self-explanatory jupyter notebook:
Col-OSSOS: [TNO_paper_Col-OSSOS.ipynb](https://github.com/ZehaoJin/causalTNOs/blob/main/TNO_paper_Col-OSSOS.ipynb)
DES: [TNO_paper_DES.ipynb](https://github.com/ZehaoJin/causalTNOs/blob/main/TNO_paper_DES.ipynb)


You might need following python packages:

      causallearn
      sklearn
      seaborn
      pydot
## 3. Cite this work
If you use this repository or would like to refer the paper, please use the following BibTeX entry:

      @article{Davis2025causal,
    author = {Davis, Benjamin L and Ali-Dib, Mohamad and Zheng, Yujia and Jin, Zehao and Zhang, Kun and Macciò, Andrea Valerio},
    title = {Causal evidence for the primordiality of colours in trans-Neptunian objects},
    journal = {Monthly Notices of the Royal Astronomical Society: Letters},
    pages = {slaf089},
    year = {2025},
    month = {08},
    abstract = {The origins of the colours of Trans-Neptunian Objects (TNOs) represent a crucial unresolved question, central to understanding the history of our Solar System. Recent observational surveys revealed correlations between the eccentricity and inclination of TNOs, and their colours. This rekindled the long-standing debate on whether these colours reflect the conditions of TNO formation or their subsequent evolution. We address this question using a model-agnostic, data-driven approach that unanimously converges to a common causal graph from the analysis of two different datasets, each from two different conditional independence test methods. For evaluation, we demonstrate how our model is consistent with the currently-accepted paradigms of TNOs’ dynamical histories, without involving any orbital modelling or physics-based assumptions. Our causal model (with no knowledge of the existence of Neptune) predicts the need for an unknown confounding variable, consistent with Neptune’s effects. The model predicts that the colour of TNOs is the root cause of their inclination distribution, rather than the other way around. This strongly suggests that the colours of TNOs reflect an underlying dynamical property, most likely their formation location. Our model excludes formation scenarios that invoke substantial colour modification by subsequent evolution. We conclude that the colours of TNOs are predominantly primordial.},
    issn = {1745-3925},
    doi = {10.1093/mnrasl/slaf089},
    url = {https://doi.org/10.1093/mnrasl/slaf089},
    eprint = {https://academic.oup.com/mnrasl/advance-article-pdf/doi/10.1093/mnrasl/slaf089/64045139/slaf089.pdf},
}



      @article{zheng2024causal,
        title={Causal-learn: Causal discovery in python},
        author={Zheng, Yujia and Huang, Biwei and Chen, Wei and Ramsey, Joseph and Gong, Mingming and Cai, Ruichu and Shimizu, Shohei and Spirtes, Peter and Zhang, Kun},
        journal={Journal of Machine Learning Research},
        volume={25},
        number={60},
        pages={1--8},
        year={2024}
      }
