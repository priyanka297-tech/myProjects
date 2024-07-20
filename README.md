Image Enhancement and Super-Resolution Using EDSR Model :-
This project focuses on enhancing and super-resolving images using a combination of OpenCV for image processing and the Enhanced Deep Super-Resolution (EDSR) model from TensorFlow Hub. 
The implemented pipeline reduces noise, sharpens the image, and increases the image resolution to produce high-quality outputs.

Key Features :-
Noise Reduction: Uses median blur to reduce noise in the input image.
Image Sharpening: Enhances image details with a sharpening kernel.
Super-Resolution: Employs the EDSR model from TensorFlow Hub for high-resolution image generation.

How It Works :-
Noise Reduction: Median blur is applied to smooth the image.
Image Sharpening: A convolutional kernel sharpens the image, enhancing its details.
Super-Resolution: The EDSR model increases the image resolution, improving overall quality and clarity.

Technologies Used :-
TensorFlow & TensorFlow Hub: For loading and using the pre-trained super-resolution model.
OpenCV: For image processing tasks such as blurring and sharpening.
NumPy: For numerical operations.
Matplotlib: For visualizing the original, enhanced, and super-resolved images.
