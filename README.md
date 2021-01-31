# Smart-Stethoscope
  ALERT: THIS DOES NOT CONTAIN THE COMPLETE CODE AND THIS REPOSITORY ISN'T UPDATED. IT'LL BE UPDATED SOON, DO CHECK OUT IN A WHILE.
## Description: 
 We're automating the detecting of wheezes and crackles in breathing noises, developing a  deep learning model to do the same and deploying it on an actual
 smart stethoscope. 
## Dataset
  the Respiratory Sound Database was created by two research teams in Portugal and Greece. 
  It includes 920 annotated recordings of varying length - 10s to 90s. 
  These recordings were taken from 126 patients. 
  There are a total of 5.5 hours of recordings containing 6898 respiratory cycles - 1864 contain crackles, 886 contain wheezes and 506 contain both 
  crackles and wheezes. The data includes both clean respiratory sounds as well as noisy recordings that simulate real life conditions. 
  The patients span all age groups - children, adults and the elderly.

  This Kaggle dataset includes:

    920 .wav sound files
    920 annotation .txt files
    A text file listing the diagnosis for each patient
    A text file explaining the file naming format
    A text file listing 91 names (filename_differences.txt )
    A text file containing demographic information for each patient

## Data processing technique
   Multiple data processing techniques were used to prepare the audio files for training a CNN. Multiple filters were applied on the downsampled clips.
   Involving, feature extraction, VLTP, data augmentation and feature impoutation.
   
## Algorithm used
  A cnn built was as followed:
  
## Technologis used were:
  1. Python3
  2. Tensorflow
  3. Librosa
  4. Deep Learning
  5. IOT (to connect to the stethoscope)
  6. Feature Encoding
  7. Digital Signal Processing
