# Deep Learning for Visual Recognition
## AlexNet-Based Convolutional Neural Networks for Plant Leaf Disease Classification
Final project for Deep Learning for Visual Recognition course (10 ETC).
**Contributors:**
- Marina Ramírez Baños
- Aakriti Singh (https://github.com/Aakriti1902) 
- Eftychia Daskalaki

## Abstract
An accurate image-based detection of plant disease remains challenging. Previously built CNN
models trained on images taken under controlled conditions - as PlantVillage dataset images - often
perform poorly on real-world images. Mohanty et al. (2016) achieved 99.27% accuracy training
and testing a CNN model on PlantVillage using AlexNet, but the performance dropped to 31.4% on
external images. Building upon their approach, we developed an AlexNet-based CNN with transfer
learning and fine-tuning to detect plant diseases in PlantVillage images and in external datasets,
including PlantDoc and FieldPlantVillage. The baseline model trained only on PlantVillage achieved
97.77% accuracy on PlantVillage, but 19.49% and 29.17% on PlantDoc and FieldPlantVillage,
respectively. Including PlantDoc images in training improved accuracy to 44.92% on PlantDoc and
49.63% on FieldPlantVillage, while fine-tuning provided no significant further improvement.

## Dataset Sources
We used external public datasets:
- PlantVillage: https://github.com/spMohanty/PlantVillage-Dataset
- PlantDoc: https://github.com/pratikkayal/PlantDoc-Dataset
- Apple Classes: https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7/data
- Crop Disease Detection: https://www.kaggle.com/datasets/nirmalsankalana/crop-pest-and-disease-detection/data
- FieldPlantVillage: https://github.com/PatrickGui/FPDR/tree/master/data/Field-PlantVillage
