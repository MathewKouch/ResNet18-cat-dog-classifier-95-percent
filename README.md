# ResNet18-cat-dog-classifier-95-percent

A ResNet18 based model to distinguish cat pics from dog pics. 

A binary classifier trained via transfer learning of ResNet18 on the cats-vs-dogs Kaggle dataset of 12.5K cats and 12.5K dogs photos with accuracy of 95%.

Details of training:
    batch_size = 128
    transforms = Resize(224,224), Normalisation
    EPOCHS = 1
    lr = 0.001
    optimizer = Adam
    criterion = CrossEntropyLoss
