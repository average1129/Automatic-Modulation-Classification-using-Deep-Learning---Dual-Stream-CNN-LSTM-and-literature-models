# Requirements

## Introduction 

*	Despite regulations by governments and regulating authorities, the signal space is a very noisy environment.

*	A large number of applications require identification and monitoring of all these signals, both for civilian and military applications. 

*	The next evolution in wireless communications systems is the development of Cognitive radio, Dynamic Spectrum Access is a fundamental part of Cognitive Radio. For this transceiver should be able to gather information about its environment. 

*	There is a need to know what kind of signals are being transmitted at any given point in time 

*	Modulation Recognition is the task of classifying the modulation type of a received radio signal

## Research 

*	In the past, manual modulation recognition was implemented based on a number of measured parameters to provide a classification of different emitters using either decision theoretic or probability based methods

*	“Convolutional Radio Modulation Recognition Networks” published in 2016 introduced the idea of using Deep Learning networks for Automatic Modulation Classification.

*There are now a large variety of deep architectures that have been developed for the purpose of Modulation Recognition. 
## Defining the System 

![alt text](https://github.com/average1129/MiniProjectSDLC/blob/main/Requirements%20%26%20Research/System%20Overview.jpg)

## 5W's & 1H 

![alt text](https://github.com/average1129/MiniProjectSDLC/blob/main/Requirements%20%26%20Research/5W1H%20.jpg)

## Requirements

### High Level Requirements 

* Must be able to train & test system remotely 
* Must be able to compare developed network's performance with publications in domain
* Low computational complexity required for real world application 
* Ability to detect and differentiate large number of modulation schemes
* System must be flexible to allow for addition of new data types
*  Ability to perform on short sample lengths
*  Should be able to work with IQ data from RF front end. 
*  Should be able to perform under realistic channel conditions  
  
### Low Level Requirements 
*  Cloud based platform required to save datasets, weights, checkpoints and model parameters, and to allow remote work during work from home
*  System should be able to determine modulation type from 128 us long windowed sample
*  Usage of benchmark datasets RML 2016.10 a and RML 2016.10b to validate results, these datasets simulate real channel conditions 
*  Ability to detect atleast 11 different modulation schemes, where 3 are analog and 8 are digital : BPSK, QPSK, 8PSK, 16QAM, 64QAM, BFSK, CPFSK, PAM4, WB-FM, AM-SSB, and AM-DSB.
*  Should provide atleast 80% accuracy for SNR's from -4 dB onwards



## Tools

* Google Colaboratory
* Python 
* Tensorflow
* Keras 
* SciPy
* Numpy 
* Pandas 
* Pickle
* Seaborn
* MatPlotLib 
