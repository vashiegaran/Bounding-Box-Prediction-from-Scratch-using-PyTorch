# Bounding-Box-Prediction-from-Scratch-using-PyTorch

The focus here is more on how to read an image and its bounding box,  resize  and  perform  augmentations  correctly,  rather  than  on  the  model itself.  The goal is to have a good grasp of the fundamental ideas behind objectdetection,  which  you  can  extend  to  get  a  better  understanding  of more complex techniques such as YOLO.

1.Dataset

2. Resizing Images and Bounding Boxes

* Convert the bounding box into an image (called mask) of the same size as the image it corresponds to. This mask would just have 0 for background and 1 for the area covered by the bounding box.


