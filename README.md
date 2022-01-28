## Dog Breed - Image Detection

### Installations
Python (3.2.0.6), make sure to have all the imports installed (e.g. via conda or pip) prior to trying out and executing this project:
  - cv2, glob, keras, matplotlib, numpy, PIL, random, sklearn, tqdm  

See folder "requirements" on this, too.

### Project Motivation
This is the final project as part of the Udacity Data Scientist Nanodegree.
It is interesting to actually use a pre-trained Convolutional Neural Network (CNN) and see how well it can predict dog breeds after very short training.

The resulting model and combining algorithm could be used as a basis for e.g. developing a Web App to try and see what dog breed gets predicted on a variety of images of dogs or human faces.

### File Descriptions
	- haarcascades:
		- haarcascade_frontalface_alt.xml - OpenCV's pretrained implementation of Haar feature-based cascade classifiers to detect human faces in images
    
	- images:
		- contains some images, provided by Udacity, that are used in the Jupyter Notebook to e.g. illustrate the problem at hand
    
	- pixabay-pics:
		- contains some images of cats, dogs, and humans to test the resulting algorithm
	- requirements:
		- folder provided by Udacity, containing details of the used Python, Keras etc. versions.
	- saved_models:
		- weights.best.from_scratch.hdf5 - best model of a CNN from scratch
		- weights.best.VGG16.hdf5        - best model based on the pre-trained CNN: VGG16 using and extending on pre-calculated bottleneck-features 
		- weights.best.resnet50.hdf5     - best model based on the pre-trained CNN: ResNet50 using and extending on pre-calculated bottleneck-features

	- CODEOWNERS:  File provided by Udacity, stating the Code-Ownership of their Authors
	
	- LICENSE.txt: File provided by Udacity, stating the License
	
	- extract_bottleneck_features.py: Python module, provided by Udacity containing some helper functions to deal with the bottleneck feature extraction
	
	- dog_app.ipynb: Jupyter Notebook to find an algorithm to determine dog breeds for dog images and resembling dog breeds for pictures of human faces.
	- report.html:   HTML version / download of that Jupyter Notebook including the outputs and answers.

### Acknowledgements

Thanks to the Udacity team for preparing this interesting project!
And thanks to all cited sources mentioned in the medium.com report on this (see link at the top of this file).

### Project Definition, Analysis, Methodology, Results and Conclusion
see medium.com report: https://medium.com/@miriam.gobel/udacity-project-dog-breed-detector-f1c905b0a49
