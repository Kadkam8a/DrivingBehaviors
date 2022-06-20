# Mushroom Classification by Toxicity 

National Autonomous University of Mexico (UNAM).

- Karime Ochoa Jacinto ([Kadkam8a](https://github.com/Kadkam8a))
- Anton Pashkov ([anton-pashkov](https://github.com/anton-pashkov))

The contents of this repository are licensed under the GNU General Public License version 3. Visit https://www.gnu.org/licenses/gpl-3.0.html for more information.

## Abstract
This article describes a machine learning project to predict the toxicity of hypothetical mushroom samples based on their physical properties using KNN and Decision Trees.
## Introduction
Collecting mushrooms (shrooming) is a popular hobby for many people; however, it is a rather dangerous activity even for the most experienced collectors because of the potential toxicity coupled with nature's mechanisms that cause that non-venomous species emulate venomous features as a protection mechanism, a phenomenon known as mimicry. As such, this project seeks to construct a reliable prediction model of mushrooms' toxicity.
## Materials and Methods
The model was implemented in the Python programming language (version 3.8), as it provides all the necessary libraries for data analysis and machine learning: [Pandas](https://pandas.pydata.org/), [Numpy](https://numpy.org/), [Matplotlib](https://matplotlib.org/), and [Scikit-learn](https://scikit-learn.org/stable/). Prior to the final version of the model, several algorithms and parameters were tested, each of which are documented in this article. The mushroom dataset used in this project was downloaded from Kaggle (https://www.kaggle.com/datasets/uciml/mushroom-classification). It contains information on the color and shape of different mushrooms' caps and gills, as well as their bruises and odors. Each mushroom is classified as poisonous (p) or edible (e).
## Conclusions
The results of this project might take the readers to the wrong direction regarding the poisonous nature of mushrooms. As mentioned in the introduction, many biological creatures employ mimicry for survival purposes, meaning that it is possible to stumble upon poisonous fungi that look like edible, and viceversa. However, at least for the data presented in the dataset, the results are extremely satisfying, and might be used as a "general rule of thumb" when classifying mushrooms.
## References
UCI Machine Learning (2017). Mushroom Classification: Safe to eat or deadly poison? Retrieved from https://www.kaggle.com/datasets/uciml/mushroom-classification.
