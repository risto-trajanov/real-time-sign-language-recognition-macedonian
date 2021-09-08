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

## Model train -> Do this in Colab

1. Run `pipeline.ipynb` in colab env
2. There are a few paths that need to be adjusted to the directory in which you will clone the repo
3. Test it with predictions.ipynb


