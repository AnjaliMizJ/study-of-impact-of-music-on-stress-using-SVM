# Study-of-the-impact-of-type-of-music-genre-for-the-stress-relief-in-male-and-female-category
This is the research project based on the EEG brain signals data. The data collected was in response to the four types ofindian songs. The dimension of the data aquired was 2562*18*48. 

To convert the data into 2-D form with respect to time the data was segregated. Shown in Data segregation.ipynb

Butterforth filter:  In the preprocessing the data was filtered using Butterforth filter in the.

DWT:  After filtering the data then passed through the Discrete Wavelet Transformation using wavelet db7 to decompose the data into the bands as Gamma Waves(30-60Hz), Beta Waves(16-30Hz), Alpha Waves(8-16Hz), Theta Waves(4-8Hz) and Delta Waves(0-4Hz) for each channel. 

SVM using polynomial kernal is used to classify non-linear data.
