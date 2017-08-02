# twitter-screencap-cropper

Recognizes the text component and the image component of a meme. 

### Motivation: 
Instagram memes, which are just screencaps of Twitter posts, typically look like the following:

![](../twitter-screencap-cropper/docs/sample_meme.jpg)

We may want to: 

1. Recognize what portion of the meme belongs to the text component.
2. Recognize what portion of the meme belongs to the image component.

<img src="./docs/sample_meme_contours" width="512px">

![](../twitter-screencap-cropper/docs/sample_meme_contours.jpg)

Once we have partitioned the meme, we can save an image of each partition for later use.

### divide-screencap.py

Prompts user for an image:

~~~
$ python divide-screencap.py
Image to crop: sample_meme.jpg
~~~

Saves two images: *sample\_meme_text.jpg* and *sample\_meme_pic.jpg* to the working directory






