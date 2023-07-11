# Deep Learning Based Phonocardiogram Signals Analysis for Cardiovascular Abnormalities Detection
Cardiovascular diseases are among the vital causes of mortality worldwide which need early detection with the use of auscultation examination. Heart diseases could be diagnosed in a convenient way of heartbeat sound analysis. Manual auscultation is time-consuming and problematic to differentiate heart sounds related to different kinds of heart abnormalities. Also, as it requires an expert in the field, it becomes costly and quite prone to human error. Due to all these issues, there is a high demand for an automatic diagnostic system, an alternative way to human examination. This research focuses on developing an Artificial Intelligence (AI) based system of the latest computational algorithms for detecting heart abnormalities from heart sounds. Heart sounds are classified as 
to be normal or abnormal from Phonocardiogram (PCG)signals. One of the recent techniques introduced in deep 
learning algorithms for audio classification is a 1-Dimensional Convolutional Neural Network (1D-CNN). This research work includes a 1D-CNN as a classification algorithm. A widely used publicly available dataset of heart sounds from PhysioNet/CinC(2016) challenge is utilized. The method acquires accuracy, sensitivity, specificity, F1 score, and precision of 95.45%, 97.44%, 93.6%, 95.45%, and 95.54% respectively. The proposed approach uses a less-complicated customized 1D-CNN algorithm, outshining most of the previous competitive methods by securing high performance that makes it appropriate for diagnosing heart diseases from PCG data.

## Data and code files
* Original Physionet Dataset: https://physionet.org/content/challenge-2016/1.0.0/
* The augmented and segmented dataset after preprocessing the original Physionet dataset is contained in the "Physionet_chunks_8sec" directory.  
* "Augmentation_and segmentation.ipynb" has the preprocessing code of augmentation and segmentation of an audio signal.
* "physionet-1d-cnn-final.ipynb" has the 1D CNN model training, testing, and evaluation code.

## Figures
* Block diagram of the proposed methodology:
![Block diagram](https://github.com/Shahid-Fakhri/Heart-Sounds-Analysis/assets/83221922/0cf0e9fe-04a2-47a9-affd-412b6229fe92)

* PCG plot and spectrogram:
![PCG and Spectrogram](https://github.com/Shahid-Fakhri/Heart-Sounds-Analysis/assets/83221922/39e786e0-7ba2-4b94-a719-b02a97790d69)

* Spectrogram of the original signal, rolled signal, and pitch-shifted signal:
![augmentaion spectrograms](https://github.com/Shahid-Fakhri/Heart-Sounds-Analysis/assets/83221922/6ede8b16-68a5-42ba-ac5d-ec6e7537e4a2)

* Proposed 1D-CNN model architecture:
![1D CNN model](https://github.com/Shahid-Fakhri/Heart-Sounds-Analysis/assets/83221922/547d7af9-2497-4aae-8399-b1713ecd09d0)

  
## Access to Material:
The material provided in this repository is made available for reference and educational purposes. You are free to use and modify the material while adhering to the terms of the license mentioned in the repository. When utilizing or referencing this material, please give appropriate credit by mentioning the original creator and the research article:

[Sayed Shahid Hussain]

* Paper: S. S. Hussain, M. Ashfaq, M. S. Khan and S. Anwar, "Deep Learning Based Phonocardiogram Signals Analysis for Cardiovascular Abnormalities Detection," 2023 International Conference on Robotics and Automation in Industry (ICRAI), Peshawar, Pakistan, 2023, pp. 1-6, doi: 10.1109/ICRAI57502.2023.10089537.
