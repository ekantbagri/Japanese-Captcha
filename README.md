# Japanese-Captcha
*Currrently under process*

This project is based on Computer Vision Using Neural Network. We discovered that Japanese uses Anime Characters as a security measure in their Captchas. It is a novel approach as no-one has made a project to break that captcha and to show that it is vulnerable and can be breached. This project would be done in a ethical way only. 

It will be using Resnet50 as a CNN( Feature extractor) and RNN using LSTM as a language model. We scraped the around 4000 images from a site ie.e www.irasutoya.com using ParseHub.

Parsehub is a scraper tool that  makes scraping easy, took around few hours to download it. The image names were informative about what is happening in the image. The images were in the set of 3, 

for ex: a boy is studying, a girl is studying, both are studying. 

We used the image name and made a caption file from it in order to use it as our dataset. 

furthur we used various filters like Mean, Median, Laplacian etc. on images in order to preprocess it. resized it and convert them into grayscale.


