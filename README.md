## Language-Diarization
Spoken language diarization (SLD) is a task to perform automatic segmentation and labeling of the languages present in a given code-switched speech utterance.

# Methodology
1. Language Detection using CNN+LSTM layered model.
2. Collect & process embeddings.
3. Extracting Subsegments. (taking data about the start point and end point)
4. Clustering using two-Gaussian GMM calibration. (reverse classification)

The code to resulting the output is not done completely but the pre-output in the clustering graph shows the result.

# Dataset
VoxlingUA107 : [https://bark.phon.ioc.ee/voxlingua107/](https://bark.phon.ioc.ee/voxlingua107/)


