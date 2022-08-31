# Project things
***

## Machine Learning and AI in Photomanipulation

The proposed idea I have for my project is taking an image and through AI and Machine Learning **ML** creating sometyhing that is a little more appealing to the eye, basic adjustments to the overall tone of the image can really make all the difference compared to a shot that is straight out of the camera. As a photographer the amount of time I spend editing images to just the basic level can take quite a while, especially if there are thousands to go through. Photomanipulation software can do it all for you but sometimes isn't the result you want plus the software (like adobe) can be costly. Therefore I want to try my hand at something along these lines. I will most likely fail but hopefully in a spectacular manner that may create an abstract piece, or succeed in which case hooray. Either basic adjustments or total abtractedness is a win in my eyes!

[Photomanipulation AI can transform images like a pro](https://www.digitalinformationworld.com/2020/07/photo-manipulation-ai-amazing-results.html)

This is particularly interesting to me as it the researchers and developers of this encoder model have used existing landscapes and terxtures to totally change the original images feel both in texture but also by adding extra details like bushes or snow etc. There is a large paper attached to the website which has them face the challenge of creating controlled manipulation on existing images. My understanding from this would be that most AI or ML photomanipulation is somewhat uncontrollable and you get what you're given

[Be Funky AI photo editor](https://www.befunky.com/features/ai-photo-editing/) 

Existing software of something I would like to try, be funky uses AI to enhance the image you present it and along with that is constantly learning so it can provide even better results in the future. A simple enhancer could be something I may be able to manage, playing with basic exposure and contrast etc. to get the image looking better than it does from the camera, improve the tones and make editing easier for someone who doesn't have the time to spend hours doing it.

[MachineRay: using AI to create abstract art](https://towardsdatascience.com/machineray-using-ai-to-create-abstract-art-39829438076a)

Robert Gonsalves created a way for Generative Adversial Network GAN to create abstract pieces of art. He gathered abstract images from wiki art that were all public domain and from there trained his GAN to random images. He mentioned he had about 850 images and that that was not really enough to properly train it. I have thousands of images but it took him 3 weeks for it to be trained whereas for time I don't think I'm going to have that long to create.
***
## Update
I have really been struggling with getting my head around AI and how it can be used effectivly or in the way that I envision it. I am considering keeping photomanipulation but dropping the machine learning aspect. The other option is changing all together and either using AI to just sort images between 'landscape' and 'portrait' folders or somehow muddling through and trying with the original idea
### Feelings
Feeling a little lost on how to proceed but with some extra thought and research I am hoping that I have an aha moment. 

## Update v2
Gans are a great way of generating and manipulating images. I have found a rather helpful GAN diagram that I can actually make sense of on [This website]{https://neptune.ai/blog/image-processing-python} To put it into words 2 models exist in a GAN, The Generator which produces images in order to trick the the other model, the discriminator which tries to determine if the image is the real one or a generated one, This is super interesting to me as the models are constantly learning and improving. The generator tries harder to produce more real looking images and the discriminator works hard to find the fakes, I suppose this is in essence what machine learning is. GAN's can be used for photo blending which is what I would want it to do!
