The goal of this project is to automatically generate captions given an image. Encoder-decoder framework is used here. Encoder is a CNN and decoder is LSTM network. Here, we used pretrained resnet-34 model for the encoder. For training, we have used the COCO dataset.
## 1. For pycocotools:
```
$ git clone https://github.com/pdollar/coco.git
$ cd coco/PythonAPI/
$ make
$ python setup.py build
$ python setup.py install
```
## 2. For downloading the dataset:
```
$ pip install -r requirements.txt
$ chmod +x download.sh
$ ./download.sh
```
