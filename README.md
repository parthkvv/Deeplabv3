pip install -r requirements.txt

Dataset - augmented PASCAL VOC 2012 dataset.

### Training

python tools/train.py

### Tensorboard check
tensorboard --logdir=runs/ --port=80

Ref:
[Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation](https://arxiv.org/abs/1802.02611)
