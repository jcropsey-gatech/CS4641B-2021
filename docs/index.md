# Rats with Hats
### Contributors:
* [Justin Cropsey](https://github.com/jcropsey-gatech)
* [David Gordon](https://github.com/DavidCGordon)
* [Daniel Kim](https://github.com/dkim857)
* [Eirene Lakshita](https://github.com/eirenelakshita)
* [Su Timurturkan](https://github.com/sutimurturkan)

### Summary Figure
![Project Infographic](../media/Rats_with_Hats_Project_Poster.jpg)

### Introduction
Albeit complex, animals think in predictable manners. This is what has allowed brain mappings. This visual cortex is the section of the brain responsible for transforming the raw signals from an animal's eyes into shapes and then into recognizable objects. 

The Allen Brain Observatory, part of the Allen Institute, has compiled "a large-scale, standardized survey of physiological activity across the mouse" brain in their [Visual Coding](http://observatory.brain-map.org/visualcoding/) dataset. This dataset includes complementary imaging techniques from multiple electrodes embedded in different regions of the mouse's brain, including the visual cortex, hippocampus, and thalamus.

For our project, we will apply the unstructured learning techniques taught in this class to categorize the data into various patterns. Afterwards, we will apply structured learning techniques to the annotated datasets to be able to predict what the visual stimulus was the mouse was observing during the recording.

### Methods
Firstly, we will apply unstructured machine learning to categorize the spatial-temporal data into clusters without regard to the visual stimulus and on a per-participant basis. We will then compare participants to gain an understanding of inter-participant generalizablity of the approach. We predict there will be distinct clustering observed per participant, presuming the visual stimuli are not degenerate in interpretation by the mouse. We believe the results will be reasonably extendable to inter-participant readings due to the similarities between brains, although some loss of precision is expected. 

Secondly, we will apply structure machine learning to the clusters and their respective labels so as to be able to predict the visual stimulus observed from a novel brain reading.

We believe such an approach will be successful because brain mapping is well-proven technology despite participants' differences. That is, even if the readings are not generalizable between individuals, the system should be able to predict what was being observed from different samplings of the same participant because brains function in a consistent manner.

Because we are using a dataset that has already been collected, there is not any additional risks to animals. The costs are expected to be moderate due to the low resolution of the images compared to contemporary image sizes. The difficulty from this project arises due to the investigators' inexperience with many of the tools (e.g., HDF5, scikit-learn).

### Results
Our experiment will have four parts to its results. The first and second, our mid-term "exams" for success, are whether the data is clusterable and whether the clustering is generalizable between participants. The third and fourth parts extend these to determine whether visual stimuli can be predicted from brain readings and whether this is generalizable among participants. Success is defined as correctly predicting the visual stimulus with a probability greater than chance alone.

### Discussion
Although a brain reading model raises many ethical questions, it also has great potential in furthering healthcare technology, particularly for people suffering from neurodenerative(e.g., Lou Gehrig's disease) or neuro-muscular (e.g., myasthenia gravis) disorders where the brain itself remains intact, but the suffer's ability to interact with the outside world is significantly impaired. This technology could be extended to provide them a means to communicate with the outside world after their motor abilities are lost.

### References
[Allen Brain Map](https://portal.brain-map.org/explore/circuits/visual-coding-neuropixels)

[Machine learning for neural decoding](https://arxiv.org/ftp/arxiv/papers/1708/1708.00909.pdf)

[Real-Time Decoding of Nonstationary Neural Activity in Motor Cortex](https://ieeexplore.ieee.org/document/4483654)

[Frank Rosenblatt: Principles of Neurodynamics: Perceptrons and the Theory of Brain Mechanisms](https://link.springer.com/chapter/10.1007/978-3-642-70911-1_20)