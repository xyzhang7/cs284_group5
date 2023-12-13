# cs284_group5
* <b>project.ipynb</b> and <b>project.html</b> : demo of different segmentation models:
  * Mask-CNN
  * Faster-RCNN
  * UNet
  * MedSAM
* <b>Final Report.pdf</b>
* <b> Models </b>: checkpoints of different models:
  * best_model_sam.pth
  * unet_model_epoch_5
  * mask_rcnn_model.pth
  * faster_rcnn_model.pth
 
  The folder is stored in google drive:<b> [models](https://drive.google.com/drive/folders/1BNq93pXRDjJXot4Y-IXFGR_PAX3OFiRO) </b><br>
  We can retrive the models by the following command:
  * Install the google drive downloader: `pip install gdown`
  * Download the models: `gdown --folder https://drive.google.com/drive/folders/1BNq93pXRDjJXot4Y-IXFGR_PAX3OFiRO`

* src : all the codes we used
  * Dataset.ipynb : Data preprocessing & augmentation
  * mask&faster_rcnn.ipynb : code used for training & evaluating mask and faster_rcnn
  * MedSam - Sohyun Shin.ipynb : code used for training & evaluating MedSAM
  * U-Net_Yujeong Yang.ipynb : code used for training & evaluating U-Net

* archives
  * Dataset_BUSI_with_GT : sample test data for demonstraing R-CNN models
  * test_data.npz : data used for the project
  * cs284a_breast cancer diagnosis : presentation
  * CS 284A Final Project Proposal (Detect, Segment and Classify Breast Ultrasound Images) : proposal
