# MATH3---ImageNoiseRemover

A MATLAB-based tool that applies frequency domain filtering to reduce noise in images and visualize the Fourier Transform process.
It provides interactive control over the filter radius, enabling users to fine-tune the balance between noise reduction and detail preservation.

Description :-

The Image Noise Remover Tool leverages Fourier Transform techniques to process images in the frequency domain.
It allows applying low-pass and high-pass filters to either remove noise or extract fine details from images.
It also supports visualization of key steps: grayscale conversion, Fourier magnitude computation, frequency shifting, and filtering results.

Features :-

Convert color images into grayscale for easier processing.
Visualize the Fourier Transform and shifted spectra.
Apply custom radius-based low-pass and high-pass filters.
Add artificial noise (Salt & Pepper) to test filtering performance.
Use digital median filtering for additional noise removal.
Display results step-by-step using organized subplots.
Interactive user inputs for custom filter radius selection.
Inverse Fast Fourier Transform (IFFT): To transform the frequency domain into the original image

Tools & Technologies :-

MATLAB: Core programming language.
Image Processing Toolbox: For handling image operations like noise addition and filtering.
Fast Fourier Transform (FFT): To transform images into the frequency domain.
Frequency Filters: To isolate low or high-frequency components.
