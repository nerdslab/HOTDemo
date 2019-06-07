# Hands-on-Tech (HOT) Machine Learning Module

**Instructors:** Mark Davenport (ECE) & Eva Dyer (BME, ECE; evadyer@gatech.edu)<br>
**Teaching assistants:** Aishwarya Balwani (Grad-ECE), Max Dabagia (Undergrad-ECE), Erik Jorgensen (Grad-ECE)

### Schedule
- 15 minutes: setup - introduction to data science and machine learning
- 30 minutes: walking through each cell of the notebook (image processing, filtering, neural net example = your own photoshop)
- 1 hour, 30 minutes: mini-projects
  - explore notebook, play with variables and parameters (15 min)
  - decide on idea to pursue, discuss with TA (15 min)
  - work on mini-project (60 min)
- 15 minutes: compiling results and images, creating small exhibit of your art and creations!
- 15 minutes: see-and-share other students’ galleries!

### Overview of concepts
- Image manipulation: Show how to use Python to perform some basic image editing (crop, adjust brightness, flip, isolate color channels, etc), as well as introducing noise into an image and then using median filtering to recover the original image.
- Image convolution: Show how using different kernels can do interesting things to an image (e.g. blur, edge detection, etc)
- Style transfer: the aim is to show students how neural networks can transform an input image to be in the style of a certain artist

### Ideas for mini-projects (questions to explore):
- What if you add noise to an image and then apply style transfer? How will model interact with different types of objects/ artifacts added to your image?
- How does the model interact with different types of images? What does it seem to be picking up in images when it transforms them?
- What happens to an image if style transfer is applied more than once? What about different styles?
- How does modifying an image before applying style transfer (flipping it, resizing it, dropping color channels, etc) affect the output? Is this the same as applying style transfer and then modifying it with the same operation?
- There are lots of other edge detection filters out there - how do some of them compare to the sobel filters? (Check out filters like Laplace, Prewitt, Scharr, and more! - take a look at https://scikit-image.org/docs/dev/api/skimage.filters.html for more ideas.)
- Are there certain types of filters that could cancel each other out? What might happen if you blur an image and then sharpen it? What happens if you repeat this process lots of times?
- What happens if you modify only certain color channels in an image? Try filtering different combinations of the R,G,B channels with different filters - what effects does this have on different images?
- Is there a way to quantify how close the new image is to the style/content images? Which one is it closer to? 

