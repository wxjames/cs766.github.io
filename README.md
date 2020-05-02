# Hand signal recognition of workers on construction site by using deep learning networks based on video data
## Abstract
In construction industry, hand signal is a simple but effective method to help an operator follow instructions from the signalman. It is of good importance for construction equipment to recognize hand signals on construction site automatically, thus increasing onsite safety and speeding up the automation of construction industry. In this project, a new dataset containing 10 kinds of hand signals for guiding tower cranes is created using ZED 2 stereo camera. The collected RGB and depth video sequences are then fed into a novel two-model hierarchical architecture which was proposed by Köpüklü et al. (2019) to realize real time hand signal recognition. In the architcture, a light CNN which is ResNet-10 is trained to detect the existence of hand signals, while a deep CNN which is ResNeXt-101 is employed to classify the hand signals. In the real time recognition process, Levenshtein distance is used as the evaluation metric for classification results. The final average Levenshtein accuracy is 0.908, which achieves satisfying performances.
## Requirements
* Pytorch
* Python3
## Dataset and trained models
The dataset and trained models will be available soon.
## Running the code
* Online test
```
bash run_online.sh
```
## Acknowledgement
I want to thank [Ahmet Gündüz](https://github.com/ahmetgunduz/Real-time-GesRec) for releasing his work so that I can build mine on top.
