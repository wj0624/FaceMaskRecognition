# Face Mask Recognition Project
Introduction to Artificial Intelligence(2023-1)
ICPBL Project by Joonho Kang and Wonjeong Lim

- Goal : Given well cropped and aligned images of non masked faces, develop a deep learning model that can classify whether a person in each image is wearing a mask or not. (Binary classification task)
- Worked in Google Colab
  
**1) Data Generation** : Use MaskTheFace tool (https://github.com/aqeelanwar/MaskTheFace)
    
**2) Data Augmentation** : Use pytorch dataloader (https://pytorch.org/tutorials/beginner/basics/data_tutorial.html)

**3) Model** : Resnet50 architecture (pretrained)

**4) Train**
   - Learning rate : 0.01
   - Learning rate scheduler : LambdaLR
   - Loss : BCEWithLogitsLoss
   - Epochs : 50
   - Batch size : 64

**5) Visualization**
  - by WandB(https://wandb.ai/home)
  - training loss and training accuracy
  - validation loss and validation accuracy
  - ROC curve and AUC
