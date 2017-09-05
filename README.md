# Siamese Instance Search for Tracking

Project page: https://staff.fnwi.uva.nl/r.tao/projects/SINT/SINT_proj.html


<img src="https://staff.fnwi.uva.nl/r.tao/projects/SINT/overview.png">

Prerequisites: Fast-RCNN https://github.com/rbgirshick/fast-rcnn  (The region-of-interest pooling layer is used in our implementation)

Trained caffe model: http://isis-data.science.uva.nl/rantao/SINT_similarity.caffemodel

After adding the normalization layer into your Fast-RCNN or Caffe, and modifying the path where necessary, you should be able to reproduce our experiments on OTB benchmark with the provided model by running 'run_SINT_OTB.py'. 

The scripts in 'scripts_prepare_training_data' shows how to process ALOV (http://alov300pp.joomlafree.it/dataset-resources.html) to prepare training data to train the Siamese network.