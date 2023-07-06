# Solder_splashes
This repositair contains more than 1500 images of PCB's (part1...part4)

The image resolution is 640x640, .bmp format

The folders contain annotations .txt files (YOLO format)

There is single class object of interest in the dataset - solder splash

If the image contain no solder splashes - there is no annotation .txt file

According the YOLOv5 model's authors recommendations, the dataset contains less than 2% of background images

The annotation and image filenames differ only in file extensions (.bmp) / (.txt)

The dataset consists of 198 PCB images with 15 MPix resolution tiled into 640x640 sub-images

Since YOLO algorithm's authors recommend at least 1000 images per class, the data augmentation was performed.


