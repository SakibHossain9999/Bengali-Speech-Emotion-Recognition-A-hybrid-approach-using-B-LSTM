# Bengali-Speech-Emotion-Recognition-A-hybrid-approach-using-B-LSTM

**This repo contains the implementation of [**Paper**](https://ieeexplore.ieee.org/abstract/document/10114510) "MJ Hasan, MS Hossain, SMN Hassan, M Al-Amin, MN Rahaman, and M.A Pranjol, "Bengali Speech Emotion Recognition: A hybrid approach using B-LSTM", 2022 4th International Conference on Electrical, Computer & Telecommunication Engineering (ICECTE), 2022, pp. 1-7, doi: 10.1109/ICECTE57896.2022.10114510."**
# Project Description

**Abstract: Bengali Speech Emotion recognition is one of the major outstanding and novel pieces of work in Bengali signal processing and the field of Bengali Artificial Intelligence (AI). The audio of human speech consists of various tones from the cochlea and vocal cords. Mel-Frequency Cepstral Coefficients (MFCC), Chroma, Gamma-Frequency Cepstral Coefficients (GFCC), and Mel Spectrogram are already state-of-the-art techniques to extract various features from human speech audio. In our study, MFCC, Chroma, and Mel-Spectrogram techniques are used to extract the features for each audio on a Bengali speech audio corpus, i.e., “SUST Bengali Emotional Speech Corpus (SUBESCO)” since no other study has used all 3 features together yet. Besides, a novel model using Bidirectional Long Short Term Memory (Bi-LSTM) is proposed using these extracted features to detect different emotions in the Bengali speech corpus. Finally, our proposed model shows an overall accuracy of 83.33% with better average precision and f1-score than the Support Vector Machine (SVM) classifier and Multi-Layer Perceptron (MLP) Classifier in detecting 7 different emotion classes.**

# DATASET
**[SUBESCO]**

# System Requirements
- Python 3.7 - (All the files from the source code are written in python hence .ipynb file)
- Tensorflow 2.8.0
- Keras 2.8.0
- Ipython 7.19.0
- PC Configuration used:
  * Operating System: Windows 10 PRO 64-bit
  * RAM: 16.0 GB RAM
  * Processor: AMD Ryzen 5 3600 6-Core Processor 3.60 GHz

 # Installation Deatils
 **!pip install IPython**

# Code Execution
**The Execution is very easy, first, clone this github repository, then code(s) of three models will be availble in their respective folder, just run the .ipynb file of each model(s) in google colab or jupiter notebook.**  

# Citation

Please cite the following paper when using this code:

```bibtex
@INPROCEEDINGS{10114510,
  author={Hasan, Md Jahid and Hossain, Mohammad Sakib and Hassan, S.M. Nazmul and Al-Amin, Mohammad and Rahaman, Md. Nakib and Pranjol, Mashuk Arefin},
  booktitle={2022 4th International Conference on Electrical, Computer & Telecommunication Engineering (ICECTE)}, 
  title={Bengali Speech Emotion Recognition: A hybrid approach using B-LSTM}, 
  year={2022},
  volume={},
  number={},
  pages={1-7},
  keywords={Support vector machines;Emotion recognition;Speech recognition;Ear;Feature extraction;Mel frequency cepstral coefficient;Artificial intelligence;Bi-LSTM;MLP classifier;SUBESCO;MFCC;Bangla Speech},
  doi={10.1109/ICECTE57896.2022.10114510}
}

