# spoof-v1
the following model is based on transfer learning -  mobile net v2

Colab link - https://colab.research.google.com/drive/16NOxLV5PlPDKRvDGN34YKWIfhvWs9QSP?usp=sharing

900 - training samples, 636 - Notspoof, 264 - Spoof

214 - testing samples, 147 - Notspoof, 167 - Spoof


Image Input  - 160 X 160, Dropout = 0.55, Training Cycles = 25, Learning Rate = 0.08, Validation set size = 20%

Validation Accuracy  - 99.4%,
Validation Loss - 0.19%

Model Arch


![ei-spoof-v1-transfer-learning-tensorflow-lite-int8-quantized-model lite](https://user-images.githubusercontent.com/65299277/180593584-51938e1a-4320-4d05-a931-413620c3b24c.png)

