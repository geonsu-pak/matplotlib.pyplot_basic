# matplotlib.pyplot_basic

## display image
Matplotlib reslies on the [Pillow](https://pillow.readthedocs.io/en/latest/) library to load image data.
image data should be Numpy arrays.


import matplotlib.pyplot as plt
import matplotlib.image as mpimg
from PIL import Image

img = mpimg.imread('../../doc/_static/stinkbug.png')
img = Image.open('../../doc/_static/stinkbug.png')
plt.imshow(img)
