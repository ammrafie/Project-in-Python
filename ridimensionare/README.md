Introduction
============================================================

This is a Content-aware Image Resizer developed in Python.

Using traditional image resizing methods we may have to sacrifice parts of the image we don't want to.
Content Aware image resizing, resizes an image based on the contents of the image. This gives us more flexibility then the common Image Resizer. This projects core algorithm is based on dynamic programming which lets us get the job done efficiently.
Though this project can produce great results on many images, it has some limitations which includes not taking features of an image into account, like face detection, and foreground & background segmentation.

There are three steps in the implementation:

| Step | Exercise file | Description                                |
|------|---------------|--------------------------------------------|
| 1    | `energy.py`   | Energy calculation                         |
| 2    | `seam.py`     | Finding the lowest-energy seam             |
| 3    | `carve.py`    | Removing seams from the image              |


Setup
-----

1. Ensure you have Python 3 installed. You can install the latest version of Python in any way you wish.

2. Install the dependencies using `pip`: `pip install -r requirements.txt`

3. Now you should be able to run the code.


Image credits
-------------

All images are free to redistribute. Attribution is not necessary, but encouraged:

- Surfer - [Kiril Dobrev](https://pixabay.com/users/kirildobrev-12266114/) on [Pixabay](https://pixabay.com/photos/blue-beach-surf-travel-surfer-4145659/)

- Arch - [Mike Goad](https://www.flickr.com/photos/exit78/) on [Flickr](https://flic.kr/p/4hxxz5)
