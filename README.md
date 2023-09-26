# wetland drainage
____

[![image](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anas-hadri/)
[![image](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white
)](https://github.com/anashadri/Drainage_ZH)
[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)
___
## Subject
Sensitivity analysis of the tool for assessing the surface area impacted by agricultural drainage for wetland protection.

## Description
As part of a collaboration between INRAE and OFB, this project aims to promote a better understanding and appropriation of the subject. 
In this project, I used numerical groundwater flow modeling to assess the impact of agricultural drainage systems on steady-state groundwater drawdown in France. My aim was to develop a simplified method using pre-existing data, such as soil properties, topography, and drainage structure dimensions. This required a thorough understanding of soil properties, determination of boundary conditions and estimation of average groundwater recharge. I created R scripts to simulate different configurations (soil type, slope, alignment, drainage depth) with Hydrus-2D, in order to analyze how these hydrodynamic parameters influence the water table and determine their impact on wetlands.


## Method

___
![Image2](https://github.com/anashadri/Drainage_ZH/assets/22259698/55b07057-2435-430d-ba76-0ef225f5c38d)
___

### Script 1
This script is used firstly to create parameter sets, using Function Sobolmartinez, and based on data on the probability densities of the selected parameters (Ks, qs, qr, a, n, R, l). Secondly, to evaluate how parameter variations affect the lateral distance of influence, based on two tests: **Sobol** _**(Sobol I.M, 1993)**_ and **HSIC**.

### Script 2 
Script allows you to run HYDRUS simulations (calculating the height of the water table under the effect of drainage, and consequently the lowering of the water table) and to recover the lateral distance of impact/influence.

### Algorithm 
___
![Image3](https://github.com/anashadri/Drainage_ZH/assets/22259698/11e7cbd5-7208-44e7-a4fd-da4e39dd792b)
___


## Conclusion

The sensitivity tests carried out as part of this internship show that saturation permeability and recharge are the most sensitive parameters for simulating the shape of the water table in steady state with the Hydrus 2D/3D software. The "α" parameter of the retention curve is also sensitive.



## Abstract
In France, any development that exceeds the threshold allowed by law and impacts a wetland requires a declaration or authorization. The farmer must respect and do the administrative procedure. This study aims to determine the area of the wetland impacted by the drainage management using a numerical approach. We used the HYDRUS 2D software, which models 2D saturated/unsaturated flow based on the Richards equation. The main objective is to calculate the lateral distance of impact for different types of wetlands and management scenarios (buried drain or ditch). Subsequently, a sensitivity analysis is conducted to identify the most influential parameters in calculating the surface impacted by a drainage structure. This will help define the required level of precision for each parameter to achieve an acceptable uncertainty on the impacted area, making the tool operational. Ultimately, this will enable the evaluation of the impact surface on the wetland and determine whether the developer is in compliance or needs to submit a declaration or obtain authorization prior to any development carried out on the wetland.
**Key words** : Drainage , Wetland, hydrodynamic modeling, drainage impact, drain, ditch, sensitivity analysis.

_____________
_____________
***HADRI ANAS***
