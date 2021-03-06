# Change Log

All notable changes to this project will be documented in this file.

## [v0.1.0]
- Extended Image class and adaption of loaded SimpleITK images to internal representation
- Functionality in image metrics to consider a fixed image mask and a moving image mask
- Functionality to derive a joint domain of the fixed and moving image. This includes center of mass alignment, creation of fixed and moving domain mask and resampling to a common pixel spacing
- Image loader class, where the 6 4DCT images of the POPI model can be loaded and cached (checkout: ImageLoader.show())
- New class for handling point sets (read, write, transformation with a displacement field and TRE calculation)
- Added a BedRemoval filter and an auto crop function
- Added a Bspline kernel registration example for 3d where all the new features are used
