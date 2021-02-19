# Treatment and HIV-1 set point viral load among men who have sex with men

This repository contains the code to reproduce the analysis of how increasing treatment prevalence impacts set point viral load (SPVL) evolution.     

This model is written in the R programming language.  It requires [EpiModel](http://www.epimodel.org), the epidemic modeling software, to be installed first, as well as [EvoNetHIV](https://github.com/EvoNetHIV).      

Within R:  
`install.packages("EpiModel")`     
`if(!require(devtools)) { install.packages("devtools") }`     
`library(devtools)`         
`devtools::install_github("EvoNetHIV/RoleSPVL")`     

### Citation
Stansfield SE, Herbeck JT, Gottlieb GS, Abernethy NF, Murphy JT, Mittler JE, Goodreau SM. Test-and-treat coverage and HIV virulence evolution among men who have sex with men. Virus Evolution: in press.

### Abstract
HIV set point viral load (SPVL), the viral load established shortly after initial infection, is a proxy for HIV virulence: higher SPVLs lead to higher risk of transmission and faster disease progression. Three models of test-and-treat scenarios, mainly in heterosexual populations, found that increasing treatment coverage selected for more virulent viruses. We modeled virulence evolution in a population of men who have sex with men (MSM) with increasing test-and-treat coverage.      
We extended a stochastic, dynamic network model (EvoNetHIV). We varied relationship patterns (MSM vs. heterosexual), HIV transmission models (increasing vs. plateauing probability of transmission at very high viral loads), and treatment roll-out (with explicit testing or fixed intervals between infection and treatment).         
In scenarios most similar to previous models (longer relational durations and the plateauing transmission function), we replicated trends previously found: increasing treatment coverage led to increased virulence (0.12 log10 increase in mean population SPVL between 20% and 100% treatment coverage). In scenarios reflecting MSM behavioral data using the increasing transmission function, increasing treatment coverage selected for viruses with lower virulence (0.16 log10 decrease in mean population SPVL between 20% and 100% treatment coverage).        
These findings emphasize the impact of sexual network conditions and transmission function details on predicted epidemiological and evolutionary outcomes. Varying these features creates very different evolutionary environments, which in turn lead to opposite effects in mean population SPVL evolution. Our results suggest that, under some realistic conditions, effective test-and-treat strategies may not face the previously reported tradeoff in which increasing coverage leads to evolution of greater virulence. This suggests instead that a virtuous cycle of increasing treatment coverage and diminishing virulence is possible.      
    
*Keywords*     
HIV-1, network modeling, mathematical modeling, men who have sex with men (MSM), set point viral load, anti-retroviral therapy (ART), test-and-treat
