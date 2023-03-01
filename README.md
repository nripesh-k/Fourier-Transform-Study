
# Fourier Transform for Image Filters

This project involves the implementation of the discrete fourier transform for the purpose of digital signal prcessing which was later extended to image processing.

### Frequency domain through FFT

The Fast Fourier Transform (FFT) is an algorithm that is used to effectively compute the discrete fourier transform (DFT). The FFT is widely used in many fields, including engineering, physics, and mathematics. It is an essential tool for analyzing signals and data in various scientific and engineering applications.

#### Image
![cameraman](https://github.com/nripesh-k/Fourier-Transform-Study/blob/master/image/cameraman.jpg?raw=true)
#### Frequency Domain:
![frequency domain](https://github.com/nripesh-k/Fourier-Transform-Study/blob/master/image/cameraman-fourier-domain.png?raw=true)

### Edge Detection and Blurring

The blurring and edge detection effect can be achieved by using the low-pass and the high-pass filters in the frequency domain of the image.

#### Edge Detection

![edge detection](https://github.com/nripesh-k/Fourier-Transform-Study/blob/master/image/cameraman-edges.png?raw=true)

#### Blurring
![blur effect](https://github.com/nripesh-k/Fourier-Transform-Study/blob/master/image/cameraman-blur.png?raw=true)

(Note: The ringing effect seen in the above two images is due to the abrupt nature of the applied filters(i.e, high-pass and low-pass).)

### Convolution through the fourier property

The convolution of images can be calculated in an effective way through the use of the fourier domain propertys.

#### Convolution with a horizonatal edge detector kernel
![kernel convolution](https://github.com/nripesh-k/Fourier-Transform-Study/blob/master/image/cameraman-hed.png?raw=true)
#### Convolution with a vertical edge detector kernel
![kernel convolution](https://github.com/nripesh-k/Fourier-Transform-Study/blob/master/image/cameraman-ved.png?raw=true)

### Derivative through the fourier property

The derivative of signals can be computed through the inverse fourier transform. It is a very effective and accurate method of computing derivatives.

#### Image
![image](https://github.com/nripesh-k/Fourier-Transform-Study/blob/master/image/face.jpg?raw=true)
#### Gradient (1st Derivative)
![gradient](https://github.com/nripesh-k/Fourier-Transform-Study/blob/master/image/face-gradient-x.png?raw=true)

All these implementation and more can be found in the notebooks provided.
