[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/[PUT-YOUR-REPOSITORY-HERE]/main)

# 27410 - Group assignment - Group [13] - [Psilocybin production in Corynebacterium glutamicum]

## Project summary (<300 words)
It is desired to modify the host cell to adapt it for production of a new compound. In order to achieve this a model for Corynebacterium glutamicum (iCW773) [1] is modified, by the addition of a synthetic pathway, to allow the production of psilocybin, a hallucinogenic compound, which is currently seen as promising future medicine in order to treat depressions and other mental afflictions. For implementation of the synthetic pathway we are introducing a series of enzymatic reactions, which were already reported and successfully implemented to S. cerevisiae[2]. The synthetic pathways starts from the amino-acid L-tryptophan, which is naturally present in C. glutamicum. Previously, C. glutamicum was successfully used for the production of L-tryptophan derived products, such as violacein or brominated L-tryptophan[3], [4]. Thus, the production of psilocybin from L-tryptophan was selected as promising strategy for this project. This project is not only aiming for adding psilocybin as new product to the portfolio of C. glutamicum, but also intends to optimize the production rate and yield for psilocybin. Optimally, C. glutamicum shows higher potential for the production of psilocybin than previously engineered cell-factories such as S. cerevisiae or E.coli[2], [5].

## Project overview
This is the [README.md](README.md) file, containing a description of the project and overview of code locations.

Our main [Report](Report.ipynb) contains more details and explanation behind the code.   
This is a type 2 project, Selection and assessment of existing GSM. Code is compiled in 8 separate documents:  
1. Reaction addition is performed in [1._Add_Psilocybin_to_Coynebacterium_Model.ipynb](1._Add_Psilocybin_to_Coynebacterium_Model.ipynb)   
2. Memote model check in [2._MemoteModelCheck.ipynb](2._MemoteModelCheck.ipynb)   
3. Phenotype Phase Plane [3._Phenotype_Phase_Plane_Psilocybin.ipynb](3._Phenotype_Phase_Plane_Psilocybin.ipynb)  
4. Production Flux Investigation [4._Production_Rate_Overview.ipynb](4._Production_Rate_Overview.ipynb)   
5. Heterologous Pathways (unsuccessful) [5._Predict_heterologous_pathways.ipynb](5._Predict_heterologous_pathways.ipynb)  
6. Cofactor swapping (unsuccessful) [6._Cofactor_swapping.ipynb](6._Cofactor_swapping.ipynb)  
7. Optgene Testing (unsuccessful) [7_Gene_Optimization.ipynb](7_Gene_Optimization.ipynb)  
8. Experimentation with Overexpression [8._FSEOF.ipynb](8._FSEOF.ipynb)  
  

Two XML files contain the model. The original Corynebacterium bacterium model [iCW773_test7.xml](iCW773_test7.xml), and modified for psilocybin production [iCW773_psilocybin.xml](iCW773_psilocybin.xml)   

Memote yielded the following reports. Original Code [MemoteReportCorynebacterium.html](MemoteReportCorynebacterium.html) and modified for psilocybin production [MemoteReportPsilocybin.html](MemoteReportPsilocybin.html).    

[requirements.txt](requirements.txt) contains packages that may be required to run the code.   


There is a [folder](Old_Files) containing old files and working copies which are no longer supported, and a [folder](Pictures) containing pictures for the report.
