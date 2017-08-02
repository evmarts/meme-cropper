# meme-cropper

Recognizes the text component and the image component of a meme. 

### Motivation: 
Instagram memes, which are just screencaps of Twitter posts, typically look like the following:

<img src="./docs/sample_meme.jpg" width="256px" alt="">

We may want to: 

1. Recognize what portion of the meme belongs to the text component.
2. Recognize what portion of the meme belongs to the image component.

<img src="./docs/sample_meme_contours.jpg" width="256px" alt="">

Once we have partitioned the meme, we can save an image of each partition for later use.

### divide-screencap.py

Prompts user for an image:

~~~
$ python divide-screencap.py
Image to crop: sample_meme.jpg
~~~

Saves two images:

~~~
Text component saved as: sample_meme_text.jpg
Image component saved as: sample_meme_pic.jpg
~~~





