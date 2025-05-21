
---
# Analog vs Digital Signals
#sampling #quantization #introduction 

### Signals
* A signal is a function containing information about the behavior of some phenomenon. Any quantity exhibiting variation over time and/or space is potentially a signal.

_a transducer converts energy from one form to another_
* Sampling discretizes the time of the signal
* Quantization discretizes the amplitude of the signal
The output of sampling and quantization is called a ==digital signal==.

* Electromagnetic energy in the visible part of the spectrum is leaving the Sun reflected by the object, travels through the air and reaches the camera. A sensor is a transducer which is an analog camera, that through photo-chemistry converts light energy into chemical changes on the film. So the brighter parts of the image. We have higher concentration of silver halide grains and this film, after it's processed, negative or black and white film, represents analog image. 

### Sampling
* Downsampling is basically done by taking one element in one pixel, disregarding the other 63 elements (assuming an 8bit pixel) 
* Upsampling (zero order hold) is done by taking that singular value and duplicate it to the other 63 elements
* Requantization involves going from a particular number of bits per pixel to another

---
# Image and Video Signals

* Images and Videos can be
	* 1D: tones, speech, biomedical, remote sensing, etc _s(t), s(n)_
	* 2D: text, grayscale, color, multispectral, hyperspectral images etc _s(x,y)_
	* 3D: video, 3D volume, etc _s(x,y,z), s(x,y,t)_
	* mD: video of a volume, etc *s(x,y,z,t)

* A disparity map gives us depth perception. It is used to map the left image onto the right image in a 3D environment (stereo images).

---
# Electromagnetic Spectrum

