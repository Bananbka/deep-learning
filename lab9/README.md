# Lab 9: fine tuning (Dogs vs. Cats)

Models are larger than the free Git LFS quota, so they are attached to the release `lab9-models`:
https://github.com/Bananbka/deep-learning/releases/tag/lab9-models

- vgg16_ft.keras - VGG16, last 2 blocks unfrozen, Adam lr=1e-4, test acc 0.9584
- inception_ft.keras - InceptionV3, last 5 modules unfrozen, SGD lr=1e-3, test acc 0.9781
- resnet_ft.keras - ResNet50V2, last 6 blocks unfrozen, SGD lr=1e-3, test acc 0.9685

Input is raw 0..255 images 150x150 (normalization is inside the model).
