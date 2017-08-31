*****************************************************************

% Purvi Agrawal and Sriram Ganapathy
% Learning and Extraction of Acoustic Patterns (LEAP) Lab
% Indian Institute of Science, Bangalore, India
% {purvi_agrawal,sriram}@ee.iisc.ernet.in

*****************************************************************

% 31-Aug-2017
% See the file LISCENSE for the licence associated with this software.

******************************************************************

Ref:
1. P. Agrawal, S. Ganapathy, “Unsupervised Modulation Filter Learning for Noise-Robust Speech Recognition,” accepted for publication in Journal of Acoustical Society of America, EL, 2017.

******************************************************************

Description:

The folder contains the MATLAB codes to extract features using unsupervised data- driven modulation filtering approach.

- The modulation filters (rate and scale separately) are learned from mel spectrograms 
  using Convolutional Restricted Boltzmann Machine (CRBM).
- Multiple filters are learned using residual approach.
- The filter selection criteria uses average hidden activation probability values.
- The mel spectrograms are filtered using the selected modulation filters 
  which are then fed as features to train DNN for building ASR.

Sequence to run :

0. Zero_example_mel_spectrogram_speech.m
1. One_example_filtLearning_Rate_crbm.m
2. Two_example_filtLearning_Scale_crbm.m
3. Three_example_filtSelection_validation.m
4. Four_hidden_prob_avg.m
5. Five_example_feature_extraction_speech_forASR.m
