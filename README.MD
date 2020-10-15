Readme for the COVID-Cough Analysis

Data:
 
- 468 Audio samples in WAV format 
  - 431 Positive Patients 
  - 37 Negative Patients 
- Includes both Males and Females 
- Age range 17-83

Process: 
1. Download and Separate the data
2. Create a DataFrame from the filenames to have an overview of the stats 
3. Create Spectrograms from the audio files 
4. Extract features from the audio files
5. Pass the data through a ML/DL Model 

Currently at Number 5. 

Next steps: 

Data Augmentation: 
- Testing with the Audio Files 
- Generating new spectrograms with random_jitter  

Other Ideas: 
- Can we use GANs here? We should be able to if we generate enough augmented data in order to train it. on track of doing Audio -> Images -> Audio 



Resources to read:
 
https://benanne.github.io/2020/03/24/audio-generation.html

https://www.kdnuggets.com/2020/02/audio-data-analysis-deep-learning-python-part-1.html

https://medium.com/@keur.plkar/audio-data-augmentation-in-python-a91600613e47

https://www.kdnuggets.com/2020/02/audio-data-analysis-deep-learning-python-part-2.html





