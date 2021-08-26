# mk-sign-language-real-time-recognition
1. `pip install -r requirements.txt`
2. Use `Image Collection.ipynb` to take the images
3. Move them to `Tensorflow/workspace/images/colectedimages` 
4. Go to `Tensorflow/labelImg` 
5. `python labelImg.py`
6. Use Open Dir and select `Tensorflow/workspace/images/colectedimages`
7. Change Save Dir to `Tensorflow/workspace/images/colectedimages`
8. View shortcuts at `Tensorflow/workspace/images/labelImg/labelImg.py` line 208 to 290
9. Annotate the images


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
