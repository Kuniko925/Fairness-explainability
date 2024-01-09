# Fairness-Explainability

## Table of Content
* [Project Description](#PD)
* [To do](#DO)
* [Reference](#RF)

<a id = "PD"></a>
## Project Description
This project aims to identify potential unfairness hidden in the machine learning decision-making process in skin lesion image mult-classification by advanced explainability methods, LIME[1] and SMILE[2]. In our problem setting, skin colour is selected as a sensitive attribute, and the coverage estimation introduced by Aslansefat et al. is the metric to measure skin colour impact. Regarding the dataset, HAM10000 is frequently employed for skin colour detection and is available publicly through Kaggle for the data scientist platform. The classification model is the EfficientNet B3, a convolution neural network architecture for image classification tasks. Through this experiment, we discerned the correlation between coverage estimation and skin colour. This novel point of view focusing on the model behaviour contributes to fairness and confidence improvement.

<a id = "DO"></a>
## To do:
[] a
[] b
[] c

<a id = "RF"></a>
## Reference
[1] Ribeiro, Marco Tulio, Sameer Singh, and Carlos Guestrin. "" Why should i trust you?" Explaining the predictions of any classifier." Proceedings of the 22nd ACM SIGKDD international conference on knowledge discovery and data mining. 2016.<br>
[2] Aslansefat, Koorosh, et al. "Explaining black boxes with a SMILE: Statistical Model-agnostic Interpretability with Local Explanations." IEEE Software (2023).

## Aknowledgement
We would like to thank DAIM, Responsible AI Hull Research Group at University of Hull for their support.
## License
This framework is available under an MIT License.
