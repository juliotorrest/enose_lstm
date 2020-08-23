# Improving the Detection of Explosives in a MOX Chemical Sensors Array with LSTM Networks

Python implementation of the code used in the paper "Improving the Detection of Explosives in a MOX Chemical Sensors Array with LSTM Networks" [1], published in IEEE Sensors Journal.

The data for this project is available at [2].

Entities throughout the world face the problem of detecting hidden explosives, where human and canine inspection might not be a viable solution. Therefore, it is important to develop fast, reliable, and portable integrated inspection systems by means of automated methods, such as electronic noses. The goal of the work presented here is to develop an accurate, fast and light-weight machine/deep learning classification model to be used in a MOX chemical sensors array (electronic nose), in order to identify explosive substances. For this paper, 140 samples were taken, combining TNT or gunpowder with either soap or toothpaste, or acquiring raw samples of those substances in amounts ranging from 0.1 g to 2 g. For the classification problem, among the different options in machine learning techniques, five models were evaluated. The implemented LSTM version of a LeNet-5 based network, classifies accurately the compounds in 100% of the cases when using only 30 seconds from the 360 obtained by the sensor array per each sample. The results of this work indicate that the proposed LSTM-based deep learning model could be easily implemented into an embedded system.

This repository contains the files with the code that implements the 5 models. Please keep in mind that all of them have been trained a number of times, each with a different time-lenght information, as described in the paper.

______________________________________________

[1] J. Torres-Tello, A. V. Guaman and S. Ko, "Improving the Detection of Explosives in a MOX Chemical Sensors Array with LSTM Networks," in IEEE Sensors Journal, doi: 10.1109/JSEN.2020.3007431.

[2] Julio Torres-Tello, Ana Guaman, Seok-Bum Ko, "Mixed explosives dataset", IEEE Dataport, 2019. [Online]. Available: http://dx.doi.org/10.21227/exkq-c076. Accessed: Jul. 25, 2020. 
