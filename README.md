# meme-cropper

Recognizes the text component and the image component of a meme. 

### Motivation: 
Instagram memes, which are just screencaps of Twitter posts, typically look like the following:

<img src="./figures/sample_meme.jpg" width="256px" alt="">

We may want to: 

1. Recognize what portion of the meme belongs to the text component.
2. Recognize what portion of the meme belongs to the image component.

<img src="./figures/sample_meme_contours.jpg" width="256px" alt="">

Once we have partitioned the meme, we can save an image of each partition for later use.

### divide-screencap.py

Prompts user for an image:

~~~
$ python meme-cropper.py
Image to crop: in/img.jpg
~~~

<img src="./figures/img.jpg" width="256px" alt=""> img.jpg

~~~
Text component saved as: out/text.jpg
~~~

<img src="./figures/text.jpg" width="256px" alt=""> text.jpg

~~~
Image component saved as: out/pic.jpg
g
~~~

<img src="./figures/pic.jpg" width="256px" alt=""> pic.jpg






