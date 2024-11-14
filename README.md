# TumorNet-Deep-Learning-Based-Brain-Tumour-Detection
## Abstract 
In medical imaging, brain tumour identification
and separation from MRI scans are crucial processes that are
necessary for early diagnosis and therapy planning. In this study,
we present TumorNet, a deep learning-based system to assess
the performance of U-Net and CNN, two state-of-the-art models
in brain tumour detection and segmentation. Because of its
encoder-decoder architecture, U-Net is renowned for its precision
in medical picture segmentation, effectively capturing even the
smallest tumour boundaries. However, CNN excels at identifying
patterns and performing feature extraction, making it highly
adaptable for image classification and object recognition tasks.
To find out how well each model performs in terms of tumour
identification, segmentation accuracy, and classification efficacy,
it will be trained and assessed separately. This comparative
analysis will shed light on the advantages and disadvantages of
each model, offering suggestions for future automated tumour
analysis applications. The findings of this study have the potential
to improve diagnosis by providing radiologists with instruments
that facilitate quicker and more precise tumour evaluations.

## Data Description
The dataset is curated from the brain imaging dataset in http://medicaldecathlon.com.
The dataset consists of a training set and a test set. Each image is of dimension 120 x 120, with a corresponding label map of the same dimension. There are four number of classes in the label map:

- 0: background
- 1: edema
- 2: non-enhancing tumour
- 3: enhancing tumour

