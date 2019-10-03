# ***This is Keras tensorflow implementation of Railcrossing area segmentation using MaskRCNN***

## Installation

- ***Install pre-requisites packages mentioned in requirements.txt***
- ***Download coco weight from [https://drive.google.com/file/d/1bYTvmMN8GfDf4l9xh2brWKLpi9UHftBn/view?usp=sharing](https://drive.google.com/file/d/1bYTvmMN8GfDf4l9xh2brWKLpi9UHftBn/view?usp=sharing)***
- ***Dowload railcrossing area segmentation weight from[https://drive.google.com/file/d/1c55CQp-hrVHcZ-7J4gf5uZ1WD__8bLUZ/view?usp=sharing](https://drive.google.com/file/d/1c55CQp-hrVHcZ-7J4gf5uZ1WD__8bLUZ/view?usp=sharing)*** 

### For Training

           python3 detect.py train --dataset=/path/to/balloon/dataset --weights=coco

### For Testing with Single Image

           python detect.py splash --weights=/path/to/weights/file.h5 --image=<URL or path to file>

### For Testing With Video 

           python3 detect.py splash --weights=last --video=<URL or path to file>

### Limitation
***It is trained on CPU using 10 epoch. so Using the pretrained weight may not predict diserable output.***
 
# :smile: Happy ~~Coding~~ Contribution :two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts:
