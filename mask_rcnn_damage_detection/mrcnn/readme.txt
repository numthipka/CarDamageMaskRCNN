config.py	: 
==================================
original config of priya git branch that doesn't edit the hyperparameters

config2.py  :
==================================
numthip create for customization train with resnet50
create on 12.7.2020




python custom.py train --dataset=E:\Workspace\MyProject\mask_rcnn_damage_detection\customImages --weights=coco

see log only owner folder :
==============================================
cd log/damage20200712T2236
tensorboard --logdir=damage20200712T2236

!tensorboard --logdir=name_of_the_folder

train 10 epoch with 5500 step per epoch 
python custom.py train --dataset=E:\Workspace\MyProject\mask_rcnn_damage_detection\customImages --weights=coco