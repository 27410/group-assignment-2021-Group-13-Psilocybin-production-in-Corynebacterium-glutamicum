[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/[PUT-YOUR-REPOSITORY-HERE]/main)

# 27410 - Group assignment - Group [13] - [Psilocybin production in Corynebacterium glutamicum]

## Project summary (<300 words)
Describe the overall aim of your project and what you have achieved.\
Psilocybin production in Corynebacterium glutamicum.

It is desired to modify the host cell to adapt it for production of new materials. A model for Corynebacterium glutamicum is modified to allow the production of psilocybin, a hallucinogenic compound, which is currently seen as promising future medicine in order to treat depressions and other mental afflictions. 
For implementation of the syntethic pathway we are introducing a series of enzymatic reactions, which were already reported and succesfully implemented to S. cerevisiae. The syntethic pathways starts from the amino-acid L-tryptophan, which is naturally present in C. glutamicum. Priviously, C. glutamicum was successfully used for the production of L-tryptophan derived products. And thus was selected for this project.

It is desired to maximize the production of psylocibin while maintaining an acceptable growth rate. For this, it is desired that the production rate and yield of psylocibin in the engineered Corynebacterium should be similar to yields reported previously using S. cerevisiae or E.coli as cell-factory. 
Gene optimization methods will be applied to the cell model (iCW773) to improve the theoretical yield of the product. 

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
8. Experimentation with Overexpression [8_FSEOF.ipynb](8_FSEOF.ipynb)  
  

Two XML files contain the model. The original Corynebacterium bacterium model [iCW773_test7.xml](iCW773_test7.xml), and modified for psilocybin production [iCW773_psilocybin.xml](iCW773_psilocybin.xml)   

Memote yielded the following reports. Original Code [MemoteReportCorynebacterium.html](MemoteReportCorynebacterium.html) and modified for psilocybin production [MemoteReportPsilocybin.html](MemoteReportPsilocybin.html).    

[requirements.txt](requirements.txt) contains packages that may be required to run the code.   


There is a [folder](Old_Files) containing old files and working copies which are no longer supported, and a [folder](Pictures) containing pictures for the report.
