fIRST TO DO :
$ sudo python3 setup.py install

To train :
imagenet model
$ python3 coco.py train --dataset=/home/ee401_2/ferdyan_train/mask-rcnn_dataset --model=imagenet

coco model
$ python3 coco.py train --dataset=/home/ee401_2/ferdyan_train/mask-rcnn_dataset

To eval :
$ python3 samples/coco/coco.py evaluate --dataset=/home/ee401_2/ferdyan_train/mask-rcnn_dataset/ --model=added_140.h5
