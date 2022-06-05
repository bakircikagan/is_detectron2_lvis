# Instance segmentation on LVIS dataset
The goal of this project was to get familiarize with detectron2 library and instance segmentation in general.

## Keystones

### 1 - Setting up the development environment
I first tried to set up detectron2 and LVIS datasets. I had no more access to ETHZ GPUs, since I did not take any ML classes this semester. Then I proceeded to try this on my computer. Unfortunately this was not possible either since the GPU of my computer did not support CUDA. Finally, I decided to use Google Colab for this project.

### 2 - Exploring Detectron2 and LVIS
Once the development environment set, I downloaded the LVISv.1 dataset on the Colab notebook. Then I scrutinized the json files and dataset registration parts in detectron2 in order to filter out the initial dataset to only consider ski pole and belt categories. 

### 3 - Training
I chose to train 4 models one Coco instance segmentation and 3 LVIS models available in detectron2 model zoo. I exceeded the GPU time limit in Google Colab and had to migrate the project to another colab notebook created from my second gooble account. This was a bit frustrating since I now need to redownload the dataset, dependencies and retrain the models.

## Challenges
As mentioned before the main challenge of this project was for me to set up a proper development environment with proper GPU support. Other than this, navigating the detectron2 library and LVIS api was suprisingly smooth since both of them are well documented and have a good community support in forums.



