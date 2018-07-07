# ImageSR for Tensorflow
### Preparation
- Python 2.7/3.4/3.5/3.6 (recommend python 3.5/3.6)
- Tensorflow 1.4+ (utilize tf.data to read training data)
### Train
- Prepare training dataset. Please download DIV2K dataset:
[link](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_train_HR.zip)
- Move the training dataset to ./DIV2K/DIV2K_train_HR
- Check the config in train.py
- Run train.py > python train.py
### Inference
We train two models: VDSR and EDSR. Models are trained 50,000 steps with batch size 64.
- Check the config in test.py
- Run test.py > python test.py
### Performance
Using our models can achieve the performance as shown in below table data:

|Dataset|Scale|Bicubic|VDSR|EDSR|
|:-|:-|:-|:-|:-|
|Set5|x4|0|0|0|

