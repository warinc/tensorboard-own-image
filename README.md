# tensorboard-own-image
tensorboard-own-image

Note: All files are in VGG_model folder.

Note: This script run with 2 classes exmaple (metadata_2_classes.tsv save in folder of embedding-logs).

Note: For Keras 2.0 need to download "vgg16_weights_tf_dim_ordering_tf_kernels.h5" and put into the folder of VGG_model.

Step to process and run script
1. Download more pictures and put into data folder.
2. Run VGG.py
3. Run vgg16-feature-extraction.py sript in order to extract picture's features. 
4. Run own-data-embedding-visualization.py script in order to embedding and visualize the images

Step to run tensorboard
1. At window command: >tensorboard --logdir=C:\tensorboard-own-image\VGG_model\embedding-logs
2. At internet explorer: http://localhost:6006

