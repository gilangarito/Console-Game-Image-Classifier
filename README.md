# Game Console Image Classifier
Data science project example using deep learning for image classification.

## Overview
In this project I built a game console classifier to identify game consoles from 3 manufacturers, namely Microsoft, Nintendo, and Sony. For someone who is new or has little information about video game, this can be useful. They could take a picture of a game console, and an app could serve them some information about the history and rules of the game. This is the underlying model for building something with those capabilities

I was able to get the model to predict the game console with 95% accuracy after minimal tuning. I was able to get the model to predict the game console with 95% accuracy after minimal tuning. For most cases, this would meet the need of an end-user of the app. To get these results, I used transfer learning on a CNN trained on resnet34. This created time efficiencies and solid results.

The confusion matrix and see the difference in error.
![Confusion Matrix](https://github.com/gilangarito/consolegame_image_classifier/blob/main/matrix_result.png)

## Data
I'm using [Fatkun Batch Download Image](https://chrome.google.com/webstore/detail/fatkun-batch-download-ima/nnjjahlikiabnchcpehcpkdeckfgnohf?hl=en) chrome extention to download the data from google image.

## Image Folder
I drag and drop photos on google drive into their respective folders and drag and drop data from google drive to the destination google colab file.

## Notes
This notebook is based of the [fastai lesson two notebook](https://github.com/fastai/course-v3/blob/master/nbs/dl1/lesson2-download.ipynb) and [Ken Jee ball image classifier](https://github.com/PlayingNumbers/ball_image_classifier).
