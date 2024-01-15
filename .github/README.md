<p align="left"> </p>

<a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT">
<a href="https://standardjs.com"><img src="https://img.shields.io/badge/code_style-standard-brightgreen.svg" alt="Standard - \Matlab Style Guide"></a>

# Fairness-Explainability

## Table of Content
* [Project Description](#PD)
* [Experiment settings](#EX)
  <!-- * [To do](#DO) -->
* [Contributors](#CN)
* [Reference](#RF)

<a id = "PD"></a>
## Project Description
<p align="justify">This project aims to identify potential unfairness hidden in the machine learning decision-making process in skin lesion image mult-classification by advanced explainability methods, LIME [1] and SMILE [2]. In our problem setting, skin colour is selected as a sensitive attribute, and the coverage estimation introduced by Aslansefat et al. is the metric to measure skin colour impact. Regarding the dataset, HAM10000 is frequently employed for skin colour detection and is available publicly through Kaggle for the data scientist platform. The classification model is the EfficientNet B3, a convolution neural network architecture for image classification tasks. Through this experiment, we discerned the correlation between coverage estimation and skin colour. This novel point of view focusing on the model behaviour contributes to fairness and confidence improvement.</p>

<a id = "EX"></a>
## Experment settings:
<p align="justify">In this project, we have two types of experiments: (1) observing the effects skin colour brings on decision-making by categorising skin colour into skin colour types and (2) monitoring the correlation of skin colour distribution and coverage estimation confidence. To simplify, we call the prior setting skin colour type experiment and the later skin colour distribution from now on.</p>

### Skin color types process
* Label skin color types
* Train a model
* Evaluate model with test dataset
* Perform explainability methods
* Calculate coverage estimation
* Plot the correlation between skin types and coverage estimation

### Skin color distribution process
* Estimate average color-channels values
* Calculate distribution shift distance from the highest color-channnels values by statistic distance methods
* Train a model
* Evaluate model with test dataset
* Perform explainability methods
* Calculate coverage estimation
* Plot the correlation between skin color distribution and coverage estimation

<a id = "DO"></a>

<!--
## To do:
[] a 
[] b
[] c
-->

<a id = "CN"></a>
## Contributors:
Kuniko Paxton<br>
Dr Koorosh Aslansefat

<a id = "RF"></a>
## Reference to XAI Method Used
<a id = "ref1"></a>
<p align="justify">[1] Ribeiro, Marco Tulio, Sameer Singh, and Carlos Guestrin. ""Why should i trust you?" Explaining the predictions of any classifier." Proceedings of the 22nd ACM SIGKDD international conference on knowledge discovery and data mining. 2016.</p>
<a id = "ref2"></a>
<p align="justify">[2] Aslansefat, Koorosh, et al. "Explaining black boxes with a SMILE: Statistical Model-agnostic Interpretability with Local Explanations." IEEE Software (2023).</p>

## Related Projects
* [Fairness-and-Explainability-CFA](https://github.com/YuyingZhao/FairExplanations-CFA) 

## Aknowledgement
We would like to thank Responsible AI Hull Research Group and DAIM at University of Hull for their support.

## License
This framework is available under an MIT License.
