# training-detr
Unofficial Colab on how to train DETR, the intelligent object detector, with your own dataset.  DETR = Detection Transformer

Note there are two methods for training DETR:</br>
1 - Fine tune the existing head.  This is the initial process I will setup here.</br>
2 - Train from scratch.  This is the next process I'll show.</br>

Generally fine tuning the pre-trained head is likely the best place to start.</br> 
Note that your dataset must be in COCO format.  

Updates - Detr is now available in detectron2 so that may be an option for some.  </br>
I've added a custom dataset class which will handle the class id remapping needed to train with DETR directly.</br>



DETR was developed and open sourced by Facebook AI Research - link to their github which should supercede any info here when in doubt:
https://github.com/facebookresearch/detr


