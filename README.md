# mk-sign-language-real-time-recognition

## Image annotation -> I did this localy, it is not tested in Colab
1. `pip install -r requirements.txt`
2. Use `Image Collection.ipynb` to take the images
3. Move them to `workspace/images/colectedimages` 
4. Go to `labelImg` folder
5. `python labelImg.py`
6. Use Open Dir and select `workspace/images/colectedimages`
7. Change Save Dir to `workspace/images/colectedimages`
8. Annotate the images
9. Go to workspace/images and run prepare-train-test.ipynb

## Label IMG Shortcuts
Ctrl + u - Load all of the images from a directory

Ctrl + r - Change the default annotation target dir

Ctrl + s - Save

w - Create a rect box

d - Next image

a - Previous image

del - Delete the selected rect box

Ctrl++ - Zoom in

Ctrl-- - Zoom out

Ctrl + d - Copy the current label and rect box

Space - Flag the current image as verified

↑→↓←Keyboard arrows to move selected rect box

## Image augmentation
1. Image augmentation done with [imgaug](https://github.com/aleju/imgaug)
2. [Link](https://github.com/risto-trajanov/real-time-sign-language-recognition-macedonian/blob/main/workspace/augmentation.ipynb) to augmentation notebook

## Model train -> Do this in Colab

1. Run `pipeline.ipynb` in colab env
2. There are a few paths that need to be adjusted to the directory in which you will clone the repo
3. Test it with predictions.ipynb

## Predictions -> Do this in Colab

1. Run `predictions.ipynb` in Colab env after you completed `pipeline.ipynb`

## To-do

1. work out the real time solution in predictions.ipynb -> Done
2. Train on more images -> Done
3. Write documentation overleaf -> Done

## Real-time preview


https://user-images.githubusercontent.com/20928090/134403004-20648ece-00da-485e-9ad6-d320d94c90c1.mov

